# ExAws.Secrets

Service module for https://github.com/ex-aws/ex_aws. Library encapsulating the operations to be performed against AWS Secrets Manager.

Due to the lack of maintenance of the [original repository](https://github.com/ex-aws/ex_aws_secretsmanager), it has been decided to make a fork and create this repository as an alternative for an updated version.

## Installation

The package can be installed by adding `ex_aws_secrets` to your list of dependencies in `mix.exs` along with `:ex_aws` and your preferred JSON codec / http client.

```elixir
def deps do
  [
    {:ex_aws, "~> 2.0"},
    {:ex_aws_secrets, "~> 1.0"},
    {:poison, "~> 3.0"},
    {:hackney, "~> 1.9"},
  ]
end
```


## License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
