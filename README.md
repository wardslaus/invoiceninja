**Invoice Ninja v 5.0**

Invoice Ninja v 5.0 is coming soon!

We will be using the lessons learnt in Invoice Ninja 4.0 to build a bigger better platform to work from. If you would like to contribute to the project we will gladly accept contributions for code, user guides, bug tracking and feedback! Please consider the following guidelines prior to submitting a pull request:

# Contribution guide.

Code Style to follow [PSR-2](https://www.php-fig.org/psr/psr-2/) standards.

All methods names to be in CamelCase

All variables names to be in snake_case

Where practical code should be strongly typed, ie your methods must return a type ie

`public function doThis() : void`

PHP > 7.1 allows the return type Nullable so there should be no circumstance a type cannot be return by using the following:

`public function doThat() ?:string`

Please include tests with PRs to ensure your code works well and integrates with the rest of the project. Please ensure suitable unit/functional/acceptance tests are included to provide code coverage.
