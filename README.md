
# JS Events
Simple Util to create Events in JS

## Usage

    import  {  Events  }  from  '@poriyaalar/js-event';
    
    const EventsEmitter = new Events();
    EventsEmitter.emit("eventName", 5);
    EventsEmitter.subscribe("eventName", (value) => {
	console.log(5);
    });


## Install

`npm i @poriyaalar/js-event` 
or
`yarn add @poriyaalar/js-event`
