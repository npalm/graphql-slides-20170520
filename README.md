# GraphQL - The next API language
The slides deck contains the slides for the talk at the Nextbuild Eindhoven (2017-05-20).

- You can view the slides via GitHub static pages [here](http://npalm.github.io/graphql-slides-20170520).

## slides
For the slides we use the [RevealJS](https://github.com/hakimel/reveal.js/) framework.
- See index.html for the slide show composition
- See markdown/* for the slide sources.

### Run the slides from sources
- You can also run the slides locally in a container from sources.
```
docker run -d -p 8080:80 --name slides \
  -v ${PWD}:/usr/share/nginx/html nginx
```
- Or use yarn
```
yarn && yarn start
```
- Open a browser [slides](http://localhost:8080/)
