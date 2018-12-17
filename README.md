# multi-nav-pagination
This is a data-table pagination plugin created by me.

It provide multiple and convinient pagination options with optimal space utilization on view page. I took references from multiple pagination plugins and merged them to create a customize one with more rich funtionality and view options

To install just put this plugin js file into your project js lib, include in html page as script and then add datatable option to use this plugin. i.e.
$(document).ready(function() {
        $('#example').dataTable( {
            "pagingType": "multiNavPaging"
        } );
    } );
