# TRMNL-DASH-Bus-Tracker-Alexandria-VA
This Plugin was adapted from the TRMNL (https://usetrmnl.com) "DC Metro Station" Plugin. DASH stop number can be found out from the https://dashbus.obaweb.org/tracker site. One needs an API Key from DASH. Below are the plugin settings:
## Polling URL(s) 
https://api.goswift.ly/real-time/alexandria-dash/predictions?stop={{ dash_stop_nr }}
## Polling Headers
Authorization={{ api_key }}
## Form Fields 
- keyname: dash_stop_nr
  field_type: string
  placeholder: '4000040'
  name: Dash Stop Number
  description: DASH stop number can be found out from the https://dashbus.obaweb.org/tracker site.
- keyname: api_key
  field_type: string
  placeholder: 'OneNeedsAnAPIKeyFromDASH'
  name: API Key
  description: DASH API key for data access
- keyname: author_bio
  name: DASH Bus Tracker Alexandria VA
  field_type: author_bio
  description: This Plugin was adapted from the TRMNL "DC Metro Station" Plugin. DASH stop number can be found out from the https://dashbus.obaweb.org/tracker site. One needs an API Key from DASH.
  email_address: johnsavu@hotmail.com
## Remove bleed margin? 
No
## Enable Dark Mode? 
No
