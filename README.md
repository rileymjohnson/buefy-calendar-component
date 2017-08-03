# Calendar

Calendar component for Vue Bulma.


## Installation

```
$ npm install git+https://github.com/rileymjohnson/buefy-calendar-component.git --save
```


## Examples

```vue
<template>
    <calendar :events="events"></calendar>
</template>

<script>
import Calendar from 'buefy-calendar-component'

export default {
  name: 'app',
  components: {
    'calendar': Calendar
  },
  data() {
      return {
          events: {
              "2017-08-02": [
                  { title: "Rehearsal", url: "http://www.google.com" }
              ]
          }
      }
  }
}
</script>
```
