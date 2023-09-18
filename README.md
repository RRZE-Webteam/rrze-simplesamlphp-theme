# RRZE SimpleSAMLphp Theme

Theme module for SimpleSAMLphp to be used together with the `rrze-sso` WP plugin.

## Installation

Clone this repository into the `modules` directory of the SimpleSAMLphp
installation as follows:

```sh
cd /path/to/simplesamlphp/modules
git clone https://github.com/RRZE-Webteam/rrze-simplesamlphp-theme.git rrze
```

## Configuration

In order to use this module as theme you need to set in the `/path/to/simplesamlphp/config/config.php`:

```text
'theme.use' => 'rrze:wordpress'
```
