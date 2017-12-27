#Datepicker der mit mBlock zusammenarbeitet

Erfordert https://github.com/FriendsOfREDAXO/ui_tools
Einbinden im Modul.

		$(document).on('mblock:add', function() {
        $('.timepicker').datetimepicker({
            locale: 'de',
            format: 'HH:mm'
        });`
