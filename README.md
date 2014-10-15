rspec_pretty_report
===================

a more pretty html report for rspec

support rspec version 2.14

install

gem install rspec_pretty_report -v 0.0.1

how to use it

edit .rspec file
add the following code to .rspec file
--format RspecHtmlFormatter 

excute 'rspec' in command line.

or you can excute rspec -f RspecHtmlFormatter  in command line without edit .rspec file


If you want to provide some generated documentation for the tests you can put comments in the rspec tests like this:

  #-> Given I have ordered a vegetarian pizza
  #-> When I eat the pizza
  #-> Then my tummy is full

The #-> notation is picked up and passed through a Gherkin syntax highlighter. So it was designed to use with Given,When,Then. But in theory you can put other text there too.

