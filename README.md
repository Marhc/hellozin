# hellozin
A collection of different ways to write "Hello World!".

### Echo on Bash

```bash
echo Hello World!
```

### Echo with parameter expansion on Bash

```bash
echo "Hello $(echo World)!"

name='World'
echo "Hello $name!"

message='Hello @!'
echo "${message/@/World}"
```

### Printf on Bash

```bash
printf 'Hello %s!\n' World
```

### Echo on Powershell

```powershell
echo 'Hello World!'
```

### Write-Host on Powershell

```powershell
Write-Host Hello World!
```

### Echo or Write-Host with interpolation on Powershell

```powershell
echo ('Hello {0}!' -f 'World')
Write-Host ('Hello {0}!' -f 'World')
```

### Print on Python

```py
print('Hello World!')
```

### Print with string interpolation on Python

```python
print('Hello %s!' % 'World')
```

### Print with format method on Python

```python
print('Hello {0}!'.format('World'))
```

### Print with f-strings on Python

```python
print(f'Hello { "World" }!')
print(f"Hello { 'World' }!")
```

### Echo, print, printf and print_r on PHP

```php
<?php
  echo "Hello World!\n";
  print("Hello World!\n");
  printf("Hello World!\n");
  print_r("Hello World!\n");
```

### Printf with string interpolation on PHP

```php
<?php
  printf("Hello %s!\n", "World");
```

### Console.log on Javascript

```javascript
console.log('Hello World!');
```

### Alert on Javascript (Browser only)

```java
alert('Hello World!');
```

### Document.write on Javascript (Browser only)

```javascript
document.write("Hello World!");
```

### Before pseudo-element on CSS

```css
body::before {
  content: "Hello World!";
}
```

### Select on SQL

```sql
SELECT 'Hello World!';
```

### HTML

```html
<!DOCTYPE html>
<html>
<head>
    <title>Hello World!</title>
</head>
<body>
    Hello World!
</body>
</html>
```

