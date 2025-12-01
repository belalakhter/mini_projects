## Features
- Minimal structure
- Scalability included
- Result and error handling
- Ring buffer for task management

## Usage
- use ```pool.New(10,resultHandler,errorHandler)``` and ```pool.Dispatch()```
- use pool.AddTask(func(... interface{}) (interface{},error)) to append tasks to the pool
