Garry's Mod Lua Google Authenticator
=========

This library can be used to check or generate the Google Authenticator's dynamic password. It also contains a fast base32 implement for Lua.

```lua
local input = "172832"
local secretKey = "TESTtestTESTtest"
if gauth.Check(secretKey, input) then
  print "Pass"
else
  print "Bad code"
end
```
