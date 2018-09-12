dType.SetIOPWM(api, address, frequency, dutyCycle,  isQueued=0)
SetIOPWM:function(address, frequency, dutyCycle, isQueued, callback){
        callback = callback || function(){}
        this.jsApi.SetIOPWM(address, frequency, dutyCycle, isQueued, callback);
    },
    GetIOPWM:function(addr, callback){
        callback = callback || function(){}
        this.jsApi.GetIOPWM(addr, callback);
    },
