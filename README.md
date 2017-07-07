Testing Workshop: Exercises
====================================


To run tests just call `composer test`. If you want to produce HTML report on which test cases passed or failed,
then run `composer test:report`. If you don't have PHP and xdebug configured on your environment, nothing wrong. Just run
`composer docker:test` or `composer docker:test:report` and previous commands will be run in isolated PHP container
with prepared environment.
