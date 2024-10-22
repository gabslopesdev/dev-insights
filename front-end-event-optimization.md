# Front End Event Optimization

## Debounce

Debounce delays the execution of a function until a specified time of inactivity has passed, ensuring it's triggered only once after repeated events stop.

## Throttle

Throttle limits a function to be executed at most once per specified time interval, regardless of how often the event occurs.

## Main Differences Between Debounce and Throttle

| Aspect         | Debounce                                               | Throttle                                       |
|----------------|--------------------------------------------------------|------------------------------------------------|
| Execution Time | Executed after a period of inactivity                  | Executes at most once per interval             |
| Timer Reset    | Resets the time with each new event                    | Does not reset; executes based on the interval |
| Common Use     | Real-time search, text input fields                    | Scroll events, resize, frequent clicks         |
| Objective      | Prevents unnecessary executions until the action stops | Limits the number of executions                |
