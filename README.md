# Exercise Tracker

This is the boilerplate for the Exercise Tracker project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/exercise-tracker

Here is a preview of the instructions:

## Your responses should have the following structures:

### Exercise:

```
{
  username: "fcc_test",
  description: "test",
  duration: 60,
  date: "Mon Jan 01 1990",
  _id: "5fb5853f734231456ccb3b05"
}
```

### User:

```
{
  username: "fcc_test",
  _id: "5fb5853f734231456ccb3b05"
}
```

### Log:

```
{
  username: "fcc_test",
  count: 1,
  _id: "5fb5853f734231456ccb3b05",
  log: [{
    description: "test",
    duration: 60,
    date: "Mon Jan 01 1990",
  }]
}
```

Hint: For the date property, the toDateString method of the Date API can be used to achieve the expected output.
