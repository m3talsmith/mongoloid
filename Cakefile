{exec} = require "child_process"

task "test", "run tests", ->
  exec "NODE_ENV=test ./node_modules/mocha/bin/mocha --compilers coffee:coffee-script --require coffee-script --require test/test_helper.coffee --colors", (error, output) ->
    console.log output
