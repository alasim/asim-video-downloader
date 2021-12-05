# asim-video-downloader

A social video downloader npm package which helps to ganerate downloadable urls for all kind of social videos

#Installation

`npm i asim-video-downloader`

then...

```
const svd = require("soft-video-downloader");

const data = svd("https://www.youtube.com/watch?v=-DEPDfN8ZYk").then(
  (result) => {
    console.log(result);
    return result;
  }
);

// output:
/*
{
  info: {
    duration: '10:08',
    thub: 'https://i.ytimg.com/vi/-DEPDfN8ZYk/hqdefault.jpg',
    title: 'Top New Zach King Magic Vines 2017 - Best Magic Tricks Ever'
  },
  links: [
    {
      href: downloadabe video url,
      text: 'MP4 720',
      video_format: 'video format: 720'
    },
    {
      href: href: downloadabe video url,
      text: 'MP4 360',
      video_format: 'video format: 360'
    }
  ]
}
*/
```
