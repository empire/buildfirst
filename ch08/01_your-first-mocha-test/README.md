# Your First Mocha Test!

Writing JavaScript unit tests honestly isn't that hard, and Mocha makes it even easier! It's pretty well documented as well, so you might want to [take a look at their documentation][1] to better understand how to customize your unit testing experience.

The first thing you'll want to do here is install the `mocha` CLI globally, so it gets added to your system `PATH`.

```shell
npm install -g mocha
```

To run the tests, simply execute Mocha in your terminal, like below.

```shell
mocha --reporter spec
```

Mocha will know to look for your tests in the `test` directory. The `spec` reporter provides a prettier output than the default.

![test.png][2]

[1]: http://visionmedia.github.io/mocha
[2]: https://raw.github.com/bevacqua/buildfirst/master/images/mocha-test.png "Mocha tests in action"