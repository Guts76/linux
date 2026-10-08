# linux

## Use awk

Replace 2000 by test_IP in the file test.log

```bash
grep -rn "2000" test.log | awk '{ gsub(/2000/, "test_IP"); print > "test.log" }' test.log
```

## Use sed

```
sed -i 's/2000/IP_CP/g' test_2.log
```
