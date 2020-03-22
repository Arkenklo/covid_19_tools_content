This repository is used as a crude datastore for data produced by [content_updates.py](https://github.com/Arkenklo/covid_19_tools/blob/master/content-change-notifier/content_updates.py).

Each time the wrapper [run_and_push.sh](https://github.com/Arkenklo/covid_19_tools/blob/master/content-change-notifier/run_and_push.sh) runs, the output gets pushed to this repo.

If needed in the future we can walk through each git commit, unwrap the pickled data, and import it into a proper datastore. But using a Github repo for now is free and easy to setup.
