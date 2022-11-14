# AListener
A plugin that allows you to add event listeners on objects. Have your code called alongside an event!

## Implementation 

### `CLIENT-SIDE`  
#### #INCLUDE SCRIPT AListener.js  
### `SERVER-SIDE` 
#### #INCLUDE SERSCRIPT alistener.min.js  

## How to reference  
### `Javascript`
#### AListener|VS.global.AListener  
  
### `VyScript`  
#### AListener

## API   

###  AListener.addEventListener(pInstance, pEventName, pFunction)
   - `pInstance`: The instance to add an event listener to  
   - `pEventName`: The name of the event to add the listener to  
   - `pFunction`: The function to be called when this event is called  
   - `desc`: Adds an event listener function to `pInstance` to call whenever `pEventName` is called  

###  AListener.removeEventListener(pInstance, pEventName, pFunction)   
   - `pInstance`: The instance to remove the event listener from  
   - `pEventName`: The name of the event to remove  
   - `pFunction`: The function to be removed  
   - `desc`: Removes an event listener function from `pInstance`   

