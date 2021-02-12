[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.3.0-blue.svg?style=flat-square)](https://php.net/)[![License MIT](https://img.shields.io/github/license/romariodevjava/opencart-module-mercadolivre?style=flat-square)](LICENSE.md)


# MercadoLivre Module for OpenCart

The development of this module is for the use of the community, I ask you to kindly contribute to the solution of bugs and adjustments to improve the code.

We will work to have more OpenSource modules, since the Platform was born with this purpose!

# Installing
First of all, create your application at https://developers.mercadolivre.com.br/devcenter, in the authentication screen, you will have the URLs for you to configure your ML app.
Don't forget to enable the notification topics: 'questions' and 'orders_`v2'. The application must have the following scopes enabled: 'read', 'offline access' and 'write'

1. Download the latest release version
2. Open your OpenCart admin -> Extensions -> Installer -> Upload the downloaded file
3. Update the changes. Open your OpenCart admin -> Extensions -> Modifications -> Update
4. Clear the Template Cache. Open your OpenCart admin -> Dashboard -> Update Theme Cache
5. Configure the Free Market Module in Extensions -> Extensions -> Select Modules -> Install the module and then edit to configure it
6. Open the Mercado Livre Extension Menu -> Authenticate -> Click on the login to authenticate your Mercado Livre user. You must use the account admin user, it cannot be a collaborator account.

** Note: In the Authentication screen, you have the url to put in the application as a redirect. **

Contributions
-------------

Did you find and fix a bug or have a feature in mind and want to contribute?

* Make a fork
* Add your feature or bug fix (git checkout -b my-new-feature)
* Commit your changes (git commit -am 'Added some feature')
* Run a push to the branch (git push origin my-new-feature)
* Submit a Pull Request
* Note: Add examples for your new feature. If your Pull Request is related to a specific version, the Pull Request should not be sent to the master branch, but to the branch corresponding to the version.

# Authors

* ** José Romário ** - * Initial work * - [romariodevjava] (https://github.com/romariodevjava)

# Contribute
[! [License MIT] (https://stc.pagseguro.uol.com.br/public/img/botoes/doacoes/209x48-doar-assina.gif)] (https://pagseguro.uol.com.br /checkout/v2/donation.html?receiverEmail=romario2009142009@hotmail.com&currency=BRL)

# Requirements to install the module
* PHP 7.3 or Higher
* OpenCart 3.0.2 or higher
* Ocmod OpenCart


# Module features
- [X] Configuration
- [X] Export products to the Free Market
- [] Update products and variations with each edition in the product - Future
- [X] Exclude deactivate and exclude product in Mercado Livre, when excluded in OpenCart
- [X] Send message automatically after sales
- [X] Notify questions in OpenCart and have the option to answer
- [X] Notify and display Free Market orders on OpenCart
- [X] Mapping of OpenCart x Free market categories
- [X] Log screen to track any errors.

## License

This project is licensed under the MIT License - see the [LICENSE.md] (LICENSE.md) file for details 
