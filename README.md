# Example

```php
$d = new CQJWT();
$m = $d->getToken("hello", "World", "abc");
var_dump($m);
var_dump($d->verify($m, "abc"));
```