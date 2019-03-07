# go-rs-youtube

## YouTube client link: https://fervent-pike-8f6aeb.netlify.com/

Create YouTube client APP according technical requirements:

1. Search box is viewed by the user when he starts the app.
2. The user inputs a request in the search box. e.g. - javascript
3. The app processes the request to YouTube REST API and displays loaded clips in form of horisontal list.
4. The horisontal list can be scrolled with a swipe. Swipe is animated, e.g. user can click and pull the list sidewise. Paging event are triggered when mouseUp is released. If a user makes X quick swipes the app lists X pages. The number of clips on a page depends on the page size (from 1 to 4 clips per page).
5. The additional navigation buttons (paging control) are set on the bottom of the page.
6. As listing the pages, the app loads new data by chunks ( 15 clips per chunk).
