# How to Remove Old Office License Information
When switching Office versions, clean up old keys:
1. Open CMD as admin.
2. Navigate to Office directory:
```
cd "C:\Program Files\Microsoft Office\Office16"
```
3. Run:
```
cscript ospp.vbs /dstatus
```
4. To remove a license:
```
cscript ospp.vbs /unpkey:XXXXX
```
> Replace `XXXXX` with the last 5 characters of the key from step 3.
---