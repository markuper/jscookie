# jscookie
Vanilla js code for manage browser cookies with intuitive api

## Examples:

### Create new cookie:

```cookie.set('test', 'test value', 2);```

this code create new cookie or replace exists cookie "test" with value "test value" for 2 days

### Retrieve cookie:

```cookie.get('test')```

this code return value for cookie with name "test"

### Remove cookie:

```cookie.remove('test');```

this code will remove cookie with name "test"

### Check ability to manage cookies in browser

```cookie.isEnabled();```

this code will return boolean value
