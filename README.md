## Yak O-Matic Pro!

To deploy on [Cloud Foundry](https://console.run.pivotal.io/download_cli):

1. `cf login` so that you are ready to go
2. `git clone https://github.com/qthrul/yak.git` the repo
3. `cd yak` to make it so
4. `bundle install` - this creates the required Gemfile.lock to let things flow
5. `cf push` to make your instance count grow
6. Watch the magic take place at [https://console.run.pivotal.io/](https://console.run.pivotal.io/)
