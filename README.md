CV
==

My CV following [JSON Resume](https://json-schema.org/) schema.

# Resume

- [PDF](out/resume.pdf)
- [HTML](http://serginator.github.io/cv2/resume.html)
- [JSON](resume.json)
- [https://registry.jsonresume.org/serginator](https://registry.jsonresume.org/serginator)

# DEV

## init repo
```sh
git clone git@github.com:serginator/cv2
cd cv2
npm i --no-save
npm run install
```

## validate resume.json
`npm test`

## generate files from resume.json
`npm start`

## deploy to jsonresume.org
`npm run deploy`
