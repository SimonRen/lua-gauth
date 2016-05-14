Garry's Mod Lua Google Authenticator
=========

This library can be used to check or generate the Google Authenticator's dynamic password. It also contains a fast base32 implement for Lua.

```lua
local input = "172832" -- What the user gives you. The code from the Google Authenticator app
local secretKey = "TESTtestTESTtest" -- The secret which is given to the user to input into the Google Authenticator app
if GAuth.Check(secretKey, input) then
  print "Pass"
else
  print "Bad code"
end
```
