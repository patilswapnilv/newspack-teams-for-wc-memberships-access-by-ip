# Archived

Merged into an internal custom code repository (https://github.com/Automattic/newspack-custom-code/commit/e0667134634458642beb5f73f30c1ab47cc43599).

---

# Newspack Teams for WooCommerce Memberships Access by IP

This Plugin is an extension for the [Teams for WooCommerce Memberships](https://woocommerce.com/products/teams-woocommerce-memberships/) plugin.

It enables public access (without a WP user having to log in) to Team Membership's restricted content based on visitor's IP address. Each Team Membership gets to define their IP addresses from which their restricted/premium content will be publicly accessible

## Usage

This plugin adds a simple settings Section to the `WooCommerce` > `Settings` > `Memberships`, called "Team Access by IP".

In those settings, you can associate custom IPv4 addresses and/or IPv4 address ranges to any existing Team Membership. 

For browser requests coming from those client IP addresses, it enables public viewing of all the Posts (no login or registration needed) which that particular Team Membership is able to view based on their Membership Plan settings.  
