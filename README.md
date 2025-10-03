# OOZ Admin Notes for Orders

Private, internal notes for WooCommerce orders — visible only to users with `manage_woocommerce`.

## Features
- Private order notes (admins/store managers only)
- Timestamp + author stored per note
- Lightweight meta box in order screen

## Requirements
- WordPress 5.8+ / PHP 7.4+
- WooCommerce 6.0+

## Installation
1. Upload the folder to `/wp-content/plugins/`.
2. Activate in **Plugins**.
3. Open any order → “Admin Notes (Private)” meta box.

## Usage
- Type a note and click **Add Note**.  
- Notes are stored in order meta and hidden from customers.

## FAQ
**Are notes emailed to customers?**  
No. They are private for admins/managers only.

## Changelog
**1.0.0** — Initial release.

## License
MIT — see [LICENSE](./LICENSE).
