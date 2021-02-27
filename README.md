# KasikornBank_Class

Unoffical Kasikornbank API Class for PHP.

```php
$kbank = new KasikornBank($username, $password, $cookie_path);

// Check if the session in the cookie is still valid. If not, then login again.
if (!$kbank->CheckSession()) {
	$kbank->Login();
}

// Get Today's Statement.
print_r($kbank->GetTodayStatement("XXX-X-XXXXX-X"));

```

---

#UPDATE 01/01/2021 | Normal use | https://m.me/sitehacker
