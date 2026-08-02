# Troubleshooting

## Issue: Website works with IP but not domain

Solution:
Check DNS A record and Nginx server_name.

---

## Issue: PHP not loading

Solution:
Restart PHP-FPM service.

sudo systemctl restart php8.3-fpm