# Meetup 10K Challenge

Project's goal is to give teams a good example of what can be achieved if performance is high on priority list.

Create views of web pages that can fit into first 10K of network payload. This can be used to provide immediate feedback to the users and therefore is very important for UX. The number of 10 comes from the fact that it can fit into first 10 TCP packets which can be sent without waiting for confirmation being sent back to server (technically, it makes ~14K, but we need to account for HTTP headers as well and they are not compressed on HTTP/1.1).

Unlike traditional challenge where whole experience is required to fit into 10K (see SixApart's [10K Apart project](https://a-k-apart.com/)), this project is to envision what is the first experience that can fit into this lofty goal. From just verifying user's destination to maybe even providing primary content or at least parts of it as a skeletal design / greybox solution. In some cases, maybe even primary action can be ready as well (e.g. a link to another page is usually achievable).

## Pages

- [Event Home](https://meetup.github.io/meetup-10k-challenge/hq-faff/events/psqszpyxkbzb/)
[![Filmstrip](/hq-faff/events/psqszpyxkbzb/filmstrip.png)](http://www.webpagetest.org/video/compare.php?tests=180719_MB_664e636bb1700c631ad07997740e1b70%2C180719_CV_7f62f49dbcf0425b23919114d83ec29a)
[![Video comparison](/hq-faff/events/psqszpyxkbzb/video_thumbnail.png)](https://youtu.be/0_EW_sO2Wm0)
- [Event Home](https://meetup.github.io/meetup-10k-challenge/hq-faff/events/25212842/) (with event image placeholder)
- [Event Home](https://meetup.github.io/meetup-10k-challenge/hq-faff/events/25212842/lazyload.html) (with event image lazy-loaded)
