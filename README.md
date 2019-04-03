# Holochain Basic Chat

[[ TEMPORARY: make sure nodejs is installed, if it isn't already: https://nodejs.org]]

First, and only the first time, run `setup.sh`

Once you've run that once, you can run this anytime: `run.sh`

Double click `app-link.webloc` to open the app in the browser, or navigate to [http://localhost:3000](http://localhost:3000).

## Reseting your system

If you run into trouble, or want to reset, here's how:

1. The Chain and DHT: these are stored in `/storage` so you can just delete that folder, or run `./clear-storage.sh`
2. Your configuration: If you want to be able to re-run `setup.sh`, first delete `priv.key` and `conductor-config.toml`. Then you can re-run `./setup.sh`.

## Built With

* [Holochain](https://developer.holochain.org/)
* [React](https://reactjs.org/)

A huge acknowledgement to Pusher for providing an open source React chat UI (https://github.com/pusher/react-slack-clone)

## Authors

* **Willem Olding** - *Initial work* - [willemolding](https://github.com/willemolding)

## License

This project is licensed under the GPL-3 License - see the [LICENSE.md](LICENSE.md) file for details

