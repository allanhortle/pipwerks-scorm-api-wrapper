# Pipwerks SCORM API Wrapper

It's a module wrapper for the wondreful pipwerks api wrapper

```
npm install --save pipwerks-scorm-api-wrapper
```

## Example
```js
import scorm from 'pipwerks-scorm-api-wrapper';

scorm.init();
var name = scorm.get('cmi.core.student_name');
scorm.set('cmi.core.lesson_status', 'completed');
scorm.quit();
```

https://github.com/pipwerks/scorm-api-wrapper
