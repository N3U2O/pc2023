# legend (regexp): C\d+ challenge number >.* challenge input or hint >>>.* python prompt <\n(content) replacement to url for next challenge
C0
>2**38
<
274877906944
C1
>K->M,O->Q,E->G
>g fmnc wms bgblr rpylqjyrc gr zw fylb. rfyrq ufyr amknsrcpq ypc dmp. bmgle gr gl zw fylb gq glcddgagclr ylb rfyr'q ufw rfgq rcvr gq qm jmle. sqgle qrpgle.kyicrpylq() gq pcamkkclbcb. lmu ynnjw ml rfc spj.
```python
import string
lc=string.ascii_lowercase
table=str.maketrans(lc, lc[2:]+lc[:2])
quote="g fmnc wms bgblr rpylqjyrc gr zw fylb. rfyrq ufyr amknsrcpq ypc dmp. bmgle gr gl zw fylb gq glcddgagclr ylb rfyr'q ufw rfgq rcvr gq qm jmle. sqgle qrpgle.kyicrpylq() gq pcamkkclbcb. lmu ynnjw ml rfc spj."
print(quote.translate(table))
```
<
>>> import string
>>> lc=string.ascii_lowercase
>>> table=str.maketrans(lc, lc[2:]+lc[:2])
>>> quote="g fmnc wms bgblr rpylqjyrc gr zw fylb. rfyrq ufyr amknsrcpq ypc dmp. bmgle gr gl zw fylb gq glcddgagclr ylb rfyr'q ufw rfgq rcvr gq qm jmle. sqgle qrpgle.kyicrpylq() gq pcamkkclbcb. lmu ynnjw ml rfc spj."
>>> print(quote.translate(table))
i hope you didnt translate it by hand. thats what computers are for. doing it in by hand is inefficient and that's why this text is so long. using string.maketrans() is recommended. now apply on the url.
>>> print('map'.translate(table))
<
ocr