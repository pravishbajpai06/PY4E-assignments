# PY4E-assignment-6.5
#Solution to assignment 6.5
text = "X-DSPAM-Confidence:    0.8475";
zer=text.find("0")
pri=text[zer:]
flo=float(pri)
print(flo)

