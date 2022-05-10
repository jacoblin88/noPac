# Issue

Tool `SmbExec` targeting at windows server 2019 has some issues.
https://github.com/SecureAuthCorp/impacket/issues/777

This project annotate line 284 in `smbexec.py`

```python
#command += ' & ' + 'del ' + self.__batchFile
```