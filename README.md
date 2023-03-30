# TP-Inputs

TP-Inputs allows you to create a `Text Field` input or `Buttons Selection Inputs` with which both return the selected / typed value. 

*Fully responsive to all screen resolutions.*


**How to use Buttons Selection?**

When clicking a button, it will return `ACCEPT` or `DECLINE` values as a String.

```lua
local inputData = {
    title = "Your title",
    desc = "Your description",
    buttonparam1 = "ACCEPT",
    buttonparam2 = "DECLINE"
}
                            
TriggerEvent("tp_inputs:getButtonInput", inputData, function(cb)

    if cb == "ACCEPT" then
        -- do action
    end
end) 
```

**How to use Buttons Selection with returned values?**

When clicking a button, it will return BUY or SELL values as a String.

```lua
local inputData = {
    title = "Your title",
    desc = "Your description",
    buttonparam1 = "BUY",
    buttonparam2 = "SELL"
}
                            
TriggerEvent("tp_inputs:getButtonReturnedValuesInput", inputData, function(cb)

    if cb == "BUY" then
        -- do action
    end
end) 
```

**How to use Text Inputs?**

When clicking  `ACCEPT`  button, it will return the input text value as a String.

```lua
local inputData = {
    title = "Your title",
    desc = "Your description",
    buttonparam1 = "ACCEPT",
    buttonparam2 = "DECLINE"
}
                            
TriggerEvent("tp_inputs:getTextInput", inputData, function(cb)

    if cb == "TEST" then
        -- do action
    end
end) 
```

![image2](https://user-images.githubusercontent.com/84135181/220184654-76c6543e-054a-41ed-9eb0-adb5c3848549.png)
![image](https://user-images.githubusercontent.com/84135181/220184657-850ef2ce-2ccf-470b-8302-507aaaf7387c.png)
![4daf666e9268476a200f16ed43854f5e02e99dff](https://user-images.githubusercontent.com/84135181/228959243-0ac69849-925a-4002-9a98-070d11865c42.jpeg)



*This script will be an extra semi-requirement for my free or paid scripts and also can be used for everyone who is interested.*
