I start writing ruby in this style for quite some time and I having enjoying quite a bit

### Functions

def foo
  "bar"
end

foo = -> { "bar" }

# or if you want to resemble JS:

foo = -> { return "bar" }

# TODO: add the others

# This is good but I haven't tried it:

https://medium.com/@teabass/emulating-the-node-js-module-system-in-ruby-d84a5289d30e


# Testing library: RSpec 

Rspec.describe("app") {
  specify("this is a test") {
    test = Test.().foo()
    test.should === true
  }
}


### 


