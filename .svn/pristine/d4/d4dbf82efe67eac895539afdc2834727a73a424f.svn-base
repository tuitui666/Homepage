window.onresize = function () {
    var winW = window.innerWidth || document.documentElement.clientWidth || document.body.clientWidth;
    if (window.screen.width < 1366) { //小于1366屏幕时做屏幕缩放为768
        $('head').remove('[name="viewport"]')
        $('head').append('<meta name="viewport" content="width=768">')
    } else {
        $('head').remove('[name="viewport"]')
    }
}
