RedPotion - Template
===================

This is the default starting template for RubyMotion apps that use RedPotion (https://github.com/infinitered/redpotion).

## Install and use template

Install the RedPotion gem and use the `potion` command to create a new project.

  ```
  $ gem install redpotion
  $ potion create my_app
  ```

You shoul then load dependencies before running the project.

  ```
  $ bundle
  $ rake pod:install
  $ rake
  ```

You can use this template straight off github.

  `$ motion create --template=git@github.com:infinitered/redpotion-template.git <myappname>`

Once you've got the template locally, you can instead do:

  `$ motion create --template=redpotion-template <myappname>`


Have fun!
