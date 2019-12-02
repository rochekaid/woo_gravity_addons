# woo_gravity_addons
Connecting Woocommerce details to Gravity Form entries

This snippet will add the Woocommerce order id to the Gravity form that is linked to the order through the Gravity Forms Product Add On.  Place this code into the functions.php of a Wordpress child theme.

Your form must contain a field to add the order number.  The "$entry['1']" should be replaced by the field number in your form. For example, if your field number is 44 then change to $entry['44].
