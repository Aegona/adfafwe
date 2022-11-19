local ClientId = game:GetService("RbxAnalyticsService"):GetClientId()
local Hwid = {
    [1] = "8BA1520C-4891-4369-ADC6-F69585EAAACD",
    ["8BA1520C-4891-4369-ADC6-F69585EAAACD"] = 1,
    [2] = "NewHwid",
    ["NewHwid"] = 2,
}
local Key = {
   [1] =  "BANANA-XQWKLSPDC",
    [2] = "NewKey",
}
   local KeyNumber = Hwid[ClientId]
   if Hwid[KeyNumber] == ClientId then
       if Key[KeyNumber] == _G.Key then
           loadstring(
		game:HttpGet("https://raw.githubusercontent.com/Aegona/HOPPPPPP/main/README.md")
	)()
           else
               print("Not HaveKey")
       end
           else
               print("Not Have Hwid")
end


