moment-precise-range
====================

A moment.js plugin to display human-readable date/time ranges
Added <span> for each date part in order to style and show specific date parts on the page. 

 if (yDiff) {
            result.push('<span class="mpYear">'+pluralize(yDiff, 'year')+'</span>');
        }
        if (mDiff) {
            result.push('<span class="mpMonth">'+pluralize(mDiff, 'month')+'</span>');
        }
        if (dDiff) {
            result.push('<span class="mpDay">'+pluralize(dDiff, 'day')+'</span>');
        }
        if (hourDiff) {
            result.push('<span class="mpHour">'+pluralize(hourDiff, 'hour')+'</span>');
        }
        if (minDiff) {
            result.push('<span class="mpMinute">'+pluralize(minDiff, 'minute')+'</span>');
        }
        if (secDiff) {
            result.push('<span class="mpSecond">'+pluralize(secDiff, 'second')+'</span>');
        }
