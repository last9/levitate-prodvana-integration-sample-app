## Sample Prodvana application

``` shell
├── README.md
├── deployment.yaml
├── my-app.pvn.yaml
├── my-service.pvn.yaml
```

- Create an account on [Prodvana](https://prodvana.io).
- Clone this repository.
- Download [`pvnctl`](https://docs.prodvana.io/docs/pvnctl) CLI tool.
- Setup the application in Prodvana.

``` shell
pvnctl init
pvnctl configs apply my-app.pvn.yaml
pvnctl configs apply my-service.pvn.yaml
```

- Refer to [Prodvana docs](https://docs.prodvana.io/docs/) for more details.
- You can send deployment change events from Prodvana to Levitate. Refer to the doc [here](https://docs.prodvana.io/docs/last9).
