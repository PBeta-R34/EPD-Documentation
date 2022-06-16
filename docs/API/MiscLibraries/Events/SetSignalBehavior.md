## Function Call

```html
<Void> EPD.Events.SetSignalBehavior(<ScriptSignal> Event, <LuaNumber> Type)
```


## Description:
Sets The Event Signal Behavior <br/>

| Value		| Name 		| Meaning	                       																	|
|:----------|:---------:|--------------------------------------------------------------------------------------------------:|
| 1			| Async		| Fires Every Connected Handler In A New Thread, Ignores Any Type Of Yeilding						|
| 2			| Yeild		| Fires Each Connected Handler In A Chain, Yeilds In Each Connected Function						|
| 3			| Hybrid	| Fires Every Connected Handler In A New Thread, And Waits All Threads To Finish Before Returning	|


