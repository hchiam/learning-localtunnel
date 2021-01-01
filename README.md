# Learning [`localtunnel`](https://github.com/localtunnel/localtunnel)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

<https://github.com/localtunnel/localtunnel>

## From scratch

Using [`yarn`](https://github.com/hchiam/learning-yarn):

```bash
yarn global add localtunnel
yarn global add parcel-bundler
```

Or with `npm`:

```bash
npm install -g localtunnel
npm install -g parcel-bundler
```

And then:

```bash
touch index.html
# edit your index.html file
parcel index.html
```

Let's say [Parcel](https://github.com/hchiam/learning-parcel) is serving your index.html to localhost:1234

Then in a separate CLI:

```bash
lt --port 1234
```

You can run `npx localtunnel --port 1234` instead if you don't want to install `localtunnel`.

The CLI should print out a URL that anyone with internet access can now view, exposing/tunneled from your localhost! (Just read the warnings and then click "Click to Continue".)

## Starting by testing out this repo

Using [`yarn`](https://github.com/hchiam/learning-yarn): (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-localtunnel.git && cd learning-localtunnel && yarn && yarn go;
```

```bash
# in another CLI:
lt --port 1234 # or whichever port parcel decides
```

Or with `npm`: (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-localtunnel.git && cd learning-localtunnel && npm install && npm run go;
```

```bash
# in another CLI:
lt --port 1234 # or whichever port parcel decides
```
