# hw0405

hw0405 test case

## REMINDER

TEST CASE MAY INCORRECT.

## How to use

Input the values and output to a file

```console
./hw0405 < in/00.in > out/test00.out
```

Check differences

```console
diff out/00.out out/test00.out
```

## Changelog

### 2023.11.28

* `Two sets of identical sequences` changed from `2 han` to `3 han`:

  ```console
  Before:
  Two sets of identical sequences (2 Han)

  After:
  Two sets of identical sequences (3 Han)
  ```

* `No points hand` changed to `No-points hand` (dash added)

### 2023.11.27

* Output text modified:

  ```console
  Before:
  Is open/closed group(1: YES 0: NO):
  
  After:
  Is open group(1: YES 0: NO):
  ```

* Test case `06` output fixed: `No points hand` removed
* Test case `11` output fixed: `Three concealed triplets` added

### 2023.11.26

* Test cases added
