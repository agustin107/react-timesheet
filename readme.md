## React Timesheet
[WIP] Timesheets for you, and you, and for everybody!

## Note
No plans to make this flexible. Rather, you can *fork* or get examples from this project!

## Features
Currently ad-hoc for a private school application I'm working on.

- [x] New schedule
- [x] Edit schedule
- [x] Drag-n-drop schedule
- [x] Typehead
- [ ] Async persistence
- [ ] Async fetch
- [ ] Handle loading
- [ ] Handle errors

## Installing
```bash
npm i --save @srph/react-timesheet
```

## Usage
```js
<Timesheet time={{
  start: '10:00 AM',
  end: '10:00 PM',
  increment: { hours: 1, minutes: 30 }
}} schedules={{
  'Monday': [{
  	start: '10:00 AM',
  	end: '11:30 AM',
  	data: {}
  }]
}} />
```

See [example](examples).