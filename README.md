# Connect Widget Demo

This is a simple demo application that showcases how one might integrate MX's connect widget within your web app. You can use this and the [docs](https://developer.mx.com/moneymap/mx/#embedding-a-desktop-widget) together.

## Quick start
Clone the project and serve up `moneymap.html` with whatever server you like.

  Ruby one liner:

  ```ruby
  ruby -rwebrick -e 'WEBrick::HTTPServer.new(:Port => 8000, :DocumentRoot => Dir.pwd).start'
  ```

  Navigate to `localhost:8000/moneymap.html`


Next you need a connect widget URL. Documentation to get that is [here](https://developer.mx.com/sso/v3/#widget-urls). Once you have a URL, enter it in the input field and hit the `Open Connect` button.
