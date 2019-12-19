<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  created() {
    try {
      document.body.removeChild(document.getElementById('appLoading'))
      setTimeout(function() {
        document.getElementById('app').style.display = 'block';
      }, 500)
    } catch (e) {

    }
  }
}
</script>

<style lang="less">
.size{
  width: 100%;
  height: 100%;
}
html,body{
  .size;
  overflow: hidden;
  margin: 0;
  padding: 0;
}
#app {
  .size;
}
</style>
<style>
.ivu-icon-md-add,.ivu-icon-ios-alarm,.ivu-icon-md-albums,.ivu-icon-ios-american-football-outline,.ivu-icon-logo-android,.ivu-icon-logo-apple,.ivu-icon-md-baseball,
.ivu-icon-ios-appstore-outline,.ivu-icon-ios-arrow-back,.ivu-icon-md-arrow-dropdown,.ivu-icon-ios-arrow-dropleft-circle,.ivu-icon-md-beaker,.ivu-icon-md-bicycle,
.ivu-icon-ios-arrow-forward,.ivu-icon-md-arrow-round-down,.ivu-icon-ios-arrow-up,.ivu-icon-ios-attach,.ivu-icon-ios-barcode,.ivu-icon-md-arrow-dropright-circle,
.ivu-icon-ios-basketball-outline,.ivu-icon-md-battery-dead,.ivu-icon-ios-boat-outline,.ivu-icon-ios-bonfire,.ivu-icon-md-calendar,.ivu-icon-ios-camera-outline,
.ivu-icon-md-book,.ivu-icon-ios-bookmarks-outline,.ivu-icon-ios-briefcase,.ivu-icon-md-browsers,.ivu-icon-ios-bug,.ivu-icon-md-build,.ivu-icon-ios-bus-outline,
.ivu-icon-ios-chatboxes-outline,.ivu-icon-ios-checkbox,.ivu-icon-md-checkmark,.ivu-icon-ios-clock-outline,.ivu-icon-ios-calculator,.ivu-icon-logo-designernews,
.ivu-icon-ios-close-circle-outline,.ivu-icon-ios-cloud,.ivu-icon-md-cloud-circle,.ivu-icon-ios-cloud-download-outline,.ivu-icon-md-cloud-upload,.ivu-icon-ios-card,
.ivu-icon-ios-cloudy-night-outline,.ivu-icon-md-code-download,.ivu-icon-ios-cog-outline,.ivu-icon-ios-color-filter,.ivu-icon-md-color-palette,.ivu-icon-md-cart,
.ivu-icon-ios-compass-outline,.ivu-icon-ios-contact,.ivu-icon-md-contacts,.ivu-icon-ios-copy,.ivu-icon-md-create,.ivu-icon-ios-cube,.ivu-icon-ios-exit-outline,
.ivu-icon-ios-disc-outline,.ivu-icon-ios-done-all,.ivu-icon-logo-dribbble,.ivu-icon-ios-egg,.ivu-icon-logo-chrome,.ivu-icon-logo-facebook,.ivu-icon-md-female,
.ivu-icon-ios-eye-outline,.ivu-icon-ios-film-outline,.ivu-icon-ios-flag-outline,.ivu-icon-ios-flash,.ivu-icon-ios-funnel,.ivu-icon-md-game-controller-a,
.ivu-icon-md-git-branch,.ivu-icon-ios-git-merge,.ivu-icon-md-git-pull-request,.ivu-icon-ios-globe,.ivu-icon-ios-hammer-outline,.ivu-icon-ios-folder-outline,
.ivu-icon-md-flask,.ivu-icon-ios-football,.ivu-icon-ios-happy,.ivu-icon-md-headset,.ivu-icon-ios-help-circle,.ivu-icon-md-information,.ivu-icon-md-ionitron,
.ivu-icon-ios-grid,.ivu-icon-ios-help,.ivu-icon-md-home,.ivu-icon-ios-image,.ivu-icon-md-images,.ivu-icon-ios-ionic,.ivu-icon-ios-key,.ivu-icon-md-notifications,
.ivu-icon-md-keypad,.ivu-icon-md-leaf,.ivu-icon-ios-list,.ivu-icon-ios-locate,.ivu-icon-md-lock,.ivu-icon-ios-magnet,.ivu-icon-md-mail,.ivu-icon-ios-musical-note,
.ivu-icon-md-male,.ivu-icon-ios-map-outline,.ivu-icon-md-medal,.ivu-icon-ios-medkit-outline,.ivu-icon-ios-menu,.ivu-icon-md-mic,.ivu-icon-ios-microphone-outline,
.ivu-icon-md-remove-circle,.ivu-icon-ios-resize,.ivu-icon-ios-return-left,.ivu-icon-ios-reverse-camera-outline,.ivu-icon-ios-ribbon,.ivu-icon-md-musical-notes,
.ivu-icon-ios-nuclear,.ivu-icon-md-nutrition,.ivu-icon-ios-options,.ivu-icon-md-outlet,.ivu-icon-ios-paper-plane-outline,.ivu-icon-ios-pause,.ivu-icon-logo-sass,
.ivu-icon-md-paw,.ivu-icon-ios-person-outline,.ivu-icon-ios-phone-landscape,.ivu-icon-ios-photos-outline,.ivu-icon-ios-pin,.ivu-icon-md-pint,.ivu-icon-md-rose,
.ivu-icon-ios-plane,.ivu-icon-md-planet,.ivu-icon-ios-podium,.ivu-icon-md-power,.ivu-icon-ios-pricetags-outline,.ivu-icon-ios-pulse,.ivu-icon-ios-no-smoking-outline,
.ivu-icon-md-qr-scanner,.ivu-icon-ios-radio-outline,.ivu-icon-md-radio-button-on,.ivu-icon-ios-recording-outline,.ivu-icon-md-redo,.ivu-icon-md-refresh-circle,
.ivu-icon-ios-search-outline,.ivu-icon-ios-settings,.ivu-icon-md-share,.ivu-icon-ios-shirt-outline,.ivu-icon-ios-skip-backward-outline,.ivu-icon-ios-speedometer,
.ivu-icon-md-square,.ivu-icon-ios-star-half,.ivu-icon-md-stats,.ivu-icon-ios-subway,.ivu-icon-md-sunny,.ivu-icon-md-switch,.ivu-icon-ios-tablet-portrait,
.ivu-icon-ios-text,.ivu-icon-md-thermometer,.ivu-icon-ios-thumbs-up-outline,.ivu-icon-ios-time,.ivu-icon-md-timer,.ivu-icon-md-transgender,.ivu-icon-logo-skype,
.ivu-icon-md-trending-down,.ivu-icon-md-trophy,.ivu-icon-ios-umbrella,.ivu-icon-md-undo,.ivu-icon-ios-videocam,.ivu-icon-md-volume-down,.ivu-icon-ios-more,
.ivu-icon-ios-volume-up,.ivu-icon-ios-warning-outline,.ivu-icon-ios-water-outline,.ivu-icon-md-wifi,.ivu-icon-ios-woman,.ivu-icon-logo-yahoo{
  color: #FFAE35;
}
.ivu-icon-ios-add-circle,.ivu-icon-ios-alert,.ivu-icon-logo-angular,.ivu-icon-ios-apps,.ivu-icon-md-appstore,.ivu-icon-md-arrow-back,.ivu-icon-ios-bug-outline,
.ivu-icon-ios-arrow-dropdown-circle,.ivu-icon-md-arrow-dropleft-circle,.ivu-icon-ios-arrow-dropup,.ivu-icon-md-american-football,.ivu-icon-ios-barcode-outline,
.ivu-icon-md-arrow-forward,.ivu-icon-md-arrow-up,.ivu-icon-md-attach,.ivu-icon-ios-basket,.ivu-icon-ios-arrow-round-forward,.ivu-icon-ios-bonfire-outline,
.ivu-icon-md-basketball,.ivu-icon-ios-battery-full,.ivu-icon-ios-beer,.ivu-icon-logo-bitcoin,.ivu-icon-md-boat,.ivu-icon-ios-brush,.ivu-icon-md-bookmarks,
.ivu-icon-md-bus,.ivu-icon-ios-calculator-outline,.ivu-icon-ios-call,.ivu-icon-md-camera,.ivu-icon-ios-card-outline,.ivu-icon-ios-cash,.ivu-icon-ios-bookmark,
.ivu-icon-md-chatboxes,.ivu-icon-ios-checkbox-outline,.ivu-icon-ios-checkmark-circle,.ivu-icon-ios-clipboard,.ivu-icon-md-clock,.ivu-icon-ios-alarm-outline,
.ivu-icon-md-close-circle,.ivu-icon-ios-cloud-outline,.ivu-icon-ios-cloud-done,.ivu-icon-md-cloud-download,.ivu-icon-ios-cloudy,.ivu-icon-ios-color-wand,
.ivu-icon-md-cloudy-night,.ivu-icon-ios-code-working,.ivu-icon-md-cog,.ivu-icon-ios-color-filter-outline,.ivu-icon-ios-briefcase-outline,.ivu-icon-ios-bulb,
.ivu-icon-md-compass,.ivu-icon-ios-contact-outline,.ivu-icon-ios-contract,.ivu-icon-ios-copy-outline,.ivu-icon-ios-cube-outline,.ivu-icon-ios-egg-outline,
.ivu-icon-ios-desktop,.ivu-icon-md-disc,.ivu-icon-md-done-all,.ivu-icon-logo-dropbox,.ivu-icon-md-exit,.ivu-icon-ios-globe-outline,.ivu-icon-ios-grid-outline,
.ivu-icon-md-eye,.ivu-icon-ios-fastforward,.ivu-icon-ios-filing,.ivu-icon-md-film,.ivu-icon-md-flag,.ivu-icon-ios-flash-outline,.ivu-icon-ios-game-controller-b,
.ivu-icon-ios-flower,.ivu-icon-md-folder,.ivu-icon-ios-funnel-outline,.ivu-icon-ios-git-commit,.ivu-icon-md-git-merge,.ivu-icon-md-hammer,.ivu-icon-ios-crop,
.ivu-icon-ios-happy-outline,.ivu-icon-ios-heart,.ivu-icon-md-help,.ivu-icon-ios-help-circle-outline,.ivu-icon-ios-image-outline,.ivu-icon-ios-football-outline,
.ivu-icon-ios-infinite,.ivu-icon-ios-information-circle,.ivu-icon-ios-ionic-outline,.ivu-icon-logo-javascript,.ivu-icon-ios-key-outline,.ivu-icon-logo-html5,
.ivu-icon-logo-github,.ivu-icon-ios-laptop,.ivu-icon-ios-link,.ivu-icon-md-list,.ivu-icon-ios-locate-outline,.ivu-icon-ios-log-in,.ivu-icon-ios-magnet-outline,
.ivu-icon-ios-man,.ivu-icon-md-map,.ivu-icon-ios-medical,.ivu-icon-md-medkit,.ivu-icon-ios-menu-outline,.ivu-icon-ios-mic-off,.ivu-icon-ios-notifications-off,
.ivu-icon-ios-more-outline,.ivu-icon-ios-musical-note-outline,.ivu-icon-ios-navigate,.ivu-icon-md-no-smoking,.ivu-icon-ios-mail-open,.ivu-icon-md-microphone,
.ivu-icon-ios-nuclear-outline,.ivu-icon-logo-octocat,.ivu-icon-ios-options-outline,.ivu-icon-ios-paper,.ivu-icon-md-paper-plane,.ivu-icon-ios-pause-outline,
.ivu-icon-ios-people,.ivu-icon-md-person,.ivu-icon-md-phone-landscape,.ivu-icon-md-photos,.ivu-icon-ios-pin-outline,.ivu-icon-ios-speedometer-outline,
.ivu-icon-ios-plane-outline,.ivu-icon-ios-play,.ivu-icon-ios-podium-outline,.ivu-icon-ios-pricetag,.ivu-icon-md-pricetags,.ivu-icon-ios-pulse-outline,
.ivu-icon-ios-quote,.ivu-icon-md-radio,.ivu-icon-ios-rainy,.ivu-icon-md-recording,.ivu-icon-ios-refresh,.ivu-icon-ios-remove,.ivu-icon-logo-pinterest,
.ivu-icon-ios-reorder,.ivu-icon-md-resize,.ivu-icon-md-return-left,.ivu-icon-md-reverse-camera,.ivu-icon-ios-ribbon-outline,.ivu-icon-md-tablet-portrait,
.ivu-icon-md-square-outline,.ivu-icon-md-star-half,.ivu-icon-logo-steam,.ivu-icon-ios-subway-outline,.ivu-icon-ios-swap,.ivu-icon-ios-sync,.ivu-icon-ios-school,
.ivu-icon-ios-text-outline,.ivu-icon-ios-thumbs-down,.ivu-icon-md-thumbs-up,.ivu-icon-ios-time-outline,.ivu-icon-ios-train,.ivu-icon-ios-trash,.ivu-icon-logo-rss,
.ivu-icon-ios-trending-up,.ivu-icon-logo-tumblr,.ivu-icon-ios-umbrella-outline,.ivu-icon-ios-unlock,.ivu-icon-ios-videocam-outline,.ivu-icon-ios-volume-mute,
.ivu-icon-md-volume-up,.ivu-icon-md-warning,.ivu-icon-md-water,.ivu-icon-logo-windows,.ivu-icon-ios-woman-outline,.ivu-icon-logo-snapchat,.ivu-icon-logo-yen,
.ivu-icon-md-search,.ivu-icon-ios-settings-outline,.ivu-icon-ios-share-alt,.ivu-icon-md-shirt,.ivu-icon-md-skip-backward{
  color: #FF6A6A;
}
.ivu-icon-ios-add,.ivu-icon-md-alarm,.ivu-icon-ios-alert-outline,.ivu-icon-ios-analytics,.ivu-icon-ios-aperture,.ivu-icon-ios-expand,.ivu-icon-ios-easel,
.ivu-icon-ios-archive,.ivu-icon-ios-arrow-down,.ivu-icon-md-arrow-dropdown-circle,.ivu-icon-ios-arrow-dropright,.ivu-icon-md-arrow-dropup,.ivu-icon-md-cube,
.ivu-icon-ios-arrow-round-back,.ivu-icon-md-arrow-round-forward,.ivu-icon-ios-at,.ivu-icon-ios-backspace,.ivu-icon-md-barcode,.ivu-icon-ios-basket-outline,
.ivu-icon-ios-battery-charging,.ivu-icon-md-battery-full,.ivu-icon-ios-beer-outline,.ivu-icon-ios-bluetooth,.ivu-icon-ios-body,.ivu-icon-ios-apps-outline,
.ivu-icon-ios-bookmark-outline,.ivu-icon-ios-bowtie,.ivu-icon-md-briefcase,.ivu-icon-ios-brush-outline,.ivu-icon-ios-bulb-outline,.ivu-icon-md-calculator,
.ivu-icon-ios-cafe,.ivu-icon-ios-call-outline,.ivu-icon-ios-car,.ivu-icon-md-card,.ivu-icon-md-bug,.ivu-icon-ios-cash-outline,.ivu-icon-ios-cloudy-outline,
.ivu-icon-ios-chatbubbles,.ivu-icon-md-checkbox,.ivu-icon-ios-checkmark-circle-outline,.ivu-icon-ios-clipboard-outline,.ivu-icon-ios-close,.ivu-icon-md-egg,
.ivu-icon-ios-closed-captioning,.ivu-icon-md-cloud,.ivu-icon-ios-cloud-done-outline,.ivu-icon-md-cloud-outline,.ivu-icon-ios-crop-outline,.ivu-icon-ios-cut,
.ivu-icon-md-code-working,.ivu-icon-ios-color-fill,.ivu-icon-md-color-filter,.ivu-icon-ios-color-wand-outline,.ivu-icon-md-contract,.ivu-icon-ios-document,
.ivu-icon-ios-desktop-outline,.ivu-icon-ios-download,.ivu-icon-md-bonfire,.ivu-icon-ios-construct,.ivu-icon-md-contact,.ivu-icon-md-copy,.ivu-icon-ios-code,
.ivu-icon-ios-eye-off,.ivu-icon-ios-fastforward-outline,.ivu-icon-ios-filing-outline,.ivu-icon-ios-finger-print,.ivu-icon-ios-game-controller-b-outline,
.ivu-icon-ios-flower-outline,.ivu-icon-ios-folder-open,.ivu-icon-md-football,.ivu-icon-md-funnel,.ivu-icon-ios-flame,.ivu-icon-md-flash,.ivu-icon-ios-hand,
.ivu-icon-md-happy,.ivu-icon-ios-heart-outline,.ivu-icon-ios-help-buoy,.ivu-icon-md-help-circle,.ivu-icon-ios-ice-cream,.ivu-icon-md-image,.ivu-icon-md-grid,
.ivu-icon-ios-git-network,.ivu-icon-ios-infinite-outline,.ivu-icon-ios-information-circle-outline,.ivu-icon-md-ionic,.ivu-icon-ios-jet,.ivu-icon-md-key,
.ivu-icon-md-laptop,.ivu-icon-ios-link-outline,.ivu-icon-ios-list-box,.ivu-icon-md-locate,.ivu-icon-md-log-in,.ivu-icon-md-magnet,.ivu-icon-md-git-commit,
.ivu-icon-ios-man-outline,.ivu-icon-logo-markdown,.ivu-icon-ios-medical-outline,.ivu-icon-ios-megaphone,.ivu-icon-md-menu,.ivu-icon-ios-mic-off-outline,
.ivu-icon-md-more,.ivu-icon-ios-navigate-outline,.ivu-icon-logo-nodejs,.ivu-icon-ios-notifications-off-outline,.ivu-icon-md-globe,.ivu-icon-md-nuclear,
.ivu-icon-ios-open,.ivu-icon-md-options,.ivu-icon-ios-paper-outline,.ivu-icon-ios-partly-sunny,.ivu-icon-md-pause,.ivu-icon-ios-moon,.ivu-icon-ios-pie,
.ivu-icon-ios-people-outline,.ivu-icon-ios-person-add,.ivu-icon-ios-phone-portrait,.ivu-icon-md-pin,.ivu-icon-ios-pizza,.ivu-icon-ios-pricetag-outline,
.ivu-icon-md-plane,.ivu-icon-ios-play-outline,.ivu-icon-md-podium,.ivu-icon-ios-print,.ivu-icon-md-pulse,.ivu-icon-ios-quote-outline,.ivu-icon-md-remove,
.ivu-icon-ios-radio-button-off,.ivu-icon-ios-rainy-outline,.ivu-icon-logo-reddit,.ivu-icon-md-refresh,.ivu-icon-md-reorder,.ivu-icon-ios-restaurant,
.ivu-icon-ios-return-right,.ivu-icon-ios-rewind,.ivu-icon-md-ribbon,.ivu-icon-ios-sad,.ivu-icon-ios-school-outline,.ivu-icon-ios-send,.ivu-icon-md-settings,
.ivu-icon-ios-share-alt-outline,.ivu-icon-ios-shuffle,.ivu-icon-ios-skip-forward,.ivu-icon-ios-snow,.ivu-icon-md-speedometer,.ivu-icon-md-star-outline,
.ivu-icon-ios-star,.ivu-icon-ios-stopwatch,.ivu-icon-md-subway,.ivu-icon-md-swap,.ivu-icon-md-sync,.ivu-icon-ios-tennisball,.ivu-icon-ios-mail-open-outline,
.ivu-icon-md-text,.ivu-icon-ios-thumbs-down-outline,.ivu-icon-ios-thunderstorm,.ivu-icon-md-time,.ivu-icon-ios-train-outline,.ivu-icon-ios-trash-outline,
.ivu-icon-md-trending-up,.ivu-icon-logo-tux,.ivu-icon-md-umbrella,.ivu-icon-md-videocam,.ivu-icon-md-volume-mute,.ivu-icon-ios-glasses,.ivu-icon-ios-walk,
.ivu-icon-ios-unlock-outline,.ivu-icon-md-musical-note,.ivu-icon-ios-watch,.ivu-icon-logo-whatsapp,.ivu-icon-ios-wine,.ivu-icon-md-woman,.ivu-icon-logo-youtube{
  color: #51A6FF;
}
.ivu-icon-ios-add-circle-outline,.ivu-icon-ios-albums,.ivu-icon-md-alert,.ivu-icon-ios-analytics-outline,.ivu-icon-ios-aperture-outline,.ivu-icon-md-apps,
.ivu-icon-ios-archive-outline,.ivu-icon-md-arrow-down,.ivu-icon-ios-arrow-dropleft,.ivu-icon-md-arrow-dropright,.ivu-icon-ios-build,.ivu-icon-md-bulb,
.ivu-icon-md-arrow-round-back,.ivu-icon-ios-arrow-round-up,.ivu-icon-ios-at-outline,.ivu-icon-ios-backspace-outline,.ivu-icon-ios-arrow-dropup-circle,
.ivu-icon-md-battery-charging,.ivu-icon-ios-beaker,.ivu-icon-md-beer,.ivu-icon-md-bluetooth,.ivu-icon-ios-book,.ivu-icon-ios-baseball,.ivu-icon-md-basket,
.ivu-icon-md-bookmark,.ivu-icon-ios-bowtie-outline,.ivu-icon-ios-browsers,.ivu-icon-md-brush,.ivu-icon-ios-body-outline,.ivu-icon-md-checkmark-circle,
.ivu-icon-ios-cafe-outline,.ivu-icon-ios-calendar,.ivu-icon-md-call,.ivu-icon-ios-car-outline,.ivu-icon-ios-cart,.ivu-icon-md-cash,.ivu-icon-md-close,
.ivu-icon-ios-chatbubbles-outline,.ivu-icon-md-checkbox-outline,.ivu-icon-md-clipboard,.ivu-icon-ios-cloud-upload,.ivu-icon-md-cloudy,.ivu-icon-md-code,
.ivu-icon-ios-closed-captioning-outline,.ivu-icon-ios-cloud-circle,.ivu-icon-md-cloud-done,.ivu-icon-ios-color-fill-outline,.ivu-icon-ios-color-palette,
.ivu-icon-ios-construct-outline,.ivu-icon-ios-contacts,.ivu-icon-ios-contrast,.ivu-icon-ios-create,.ivu-icon-ios-cut-outline,.ivu-icon-md-color-wand,
.ivu-icon-md-desktop,.ivu-icon-ios-document-outline,.ivu-icon-ios-download-outline,.ivu-icon-ios-easel-outline,.ivu-icon-logo-euro,.ivu-icon-md-expand,
.ivu-icon-ios-eye-off-outline,.ivu-icon-md-fastforward,.ivu-icon-md-filing,.ivu-icon-md-finger-print,.ivu-icon-ios-flame-outline,.ivu-icon-ios-flask,
.ivu-icon-md-flower,.ivu-icon-ios-folder-open-outline,.ivu-icon-logo-foursquare,.ivu-icon-ios-game-controller-a,.ivu-icon-logo-codepen,.ivu-icon-md-crop,
.ivu-icon-ios-git-compare,.ivu-icon-md-git-network,.ivu-icon-ios-glasses-outline,.ivu-icon-logo-google,.ivu-icon-logo-hackernews,.ivu-icon-ios-hand-outline,
.ivu-icon-md-infinite,.ivu-icon-md-information-circle,.ivu-icon-ios-ionitron,.ivu-icon-ios-jet-outline,.ivu-icon-ios-keypad,.ivu-icon-md-game-controller-b,
.ivu-icon-ios-headset,.ivu-icon-md-heart,.ivu-icon-ios-help-buoy-outline,.ivu-icon-ios-home,.ivu-icon-ios-ice-cream-outline,.ivu-icon-ios-notifications,
.ivu-icon-ios-leaf,.ivu-icon-md-link,.ivu-icon-ios-list-box-outline,.ivu-icon-ios-lock,.ivu-icon-ios-log-out,.ivu-icon-ios-mail,.ivu-icon-md-mail-open,
.ivu-icon-md-man,.ivu-icon-ios-medal,.ivu-icon-md-medical,.ivu-icon-ios-megaphone-outline,.ivu-icon-ios-mic,.ivu-icon-md-mic-off,.ivu-icon-ios-moon-outline,
.ivu-icon-ios-nutrition,.ivu-icon-ios-open-outline,.ivu-icon-ios-outlet,.ivu-icon-md-paper,.ivu-icon-ios-partly-sunny-outline,.ivu-icon-ios-musical-notes,
.ivu-icon-md-people,.ivu-icon-ios-person-add-outline,.ivu-icon-md-phone-portrait,.ivu-icon-ios-pie-outline,.ivu-icon-ios-pint,.ivu-icon-ios-pizza-outline,
.ivu-icon-ios-planet,.ivu-icon-md-play,.ivu-icon-ios-power,.ivu-icon-md-pricetag,.ivu-icon-ios-print-outline,.ivu-icon-logo-python,.ivu-icon-ios-images,
.ivu-icon-ios-move,.ivu-icon-md-navigate,.ivu-icon-ios-paw,.ivu-icon-md-notifications-off,.ivu-icon-ios-tennisball-outline,.ivu-icon-md-school,
.ivu-icon-md-quote,.ivu-icon-md-radio-button-off,.ivu-icon-md-rainy,.ivu-icon-ios-redo,.ivu-icon-ios-refresh-circle,.ivu-icon-ios-remove-circle,
.ivu-icon-ios-repeat,.ivu-icon-ios-restaurant-outline,.ivu-icon-md-return-right,.ivu-icon-ios-rewind-outline,.ivu-icon-ios-rose,.ivu-icon-ios-sad-outline,
.ivu-icon-ios-send-outline,.ivu-icon-ios-share,.ivu-icon-md-share-alt,.ivu-icon-md-shuffle,.ivu-icon-ios-skip-forward-outline,.ivu-icon-ios-snow-outline,
.ivu-icon-ios-star-outline,.ivu-icon-ios-stats,.ivu-icon-ios-stopwatch-outline,.ivu-icon-ios-sunny,.ivu-icon-ios-switch,.ivu-icon-ios-tablet-landscape,
.ivu-icon-ios-thermometer,.ivu-icon-md-thumbs-down,.ivu-icon-ios-thunderstorm-outline,.ivu-icon-ios-timer,.ivu-icon-md-train,.ivu-icon-md-trash,
.ivu-icon-ios-trophy,.ivu-icon-logo-twitch,.ivu-icon-ios-undo,.ivu-icon-md-unlock,.ivu-icon-logo-vimeo,.ivu-icon-ios-volume-off,.ivu-icon-ios-square,
.ivu-icon-md-walk,.ivu-icon-md-watch,.ivu-icon-ios-wifi,.ivu-icon-ios-wine-outline,.ivu-icon-logo-wordpress,.ivu-icon-ios-loading{
  color: #35B6AE;
}
.ivu-icon-md-add-circle,.ivu-icon-ios-albums-outline,.ivu-icon-ios-american-football,.ivu-icon-md-analytics,.ivu-icon-md-aperture,.ivu-icon-ios-appstore,
.ivu-icon-md-archive,.ivu-icon-ios-arrow-dropdown,.ivu-icon-md-arrow-dropleft,.ivu-icon-ios-arrow-dropright-circle,.ivu-icon-logo-css3,.ivu-icon-md-cut,
.ivu-icon-ios-arrow-round-down,.ivu-icon-md-arrow-round-up,.ivu-icon-md-at,.ivu-icon-md-backspace,.ivu-icon-ios-baseball-outline,.ivu-icon-ios-basketball,
.ivu-icon-ios-battery-dead,.ivu-icon-ios-beaker-outline,.ivu-icon-ios-bicycle,.ivu-icon-ios-boat,.ivu-icon-md-arrow-dropup-circle,.ivu-icon-ios-compass,
.ivu-icon-ios-bookmarks,.ivu-icon-md-bowtie,.ivu-icon-ios-browsers-outline,.ivu-icon-logo-buffer,.ivu-icon-ios-build-outline,.ivu-icon-ios-cloudy-night,
.ivu-icon-md-cafe,.ivu-icon-ios-calendar-outline,.ivu-icon-ios-camera,.ivu-icon-md-car,.ivu-icon-ios-chatboxes,.ivu-icon-ios-cog,.ivu-icon-md-color-fill,
.ivu-icon-md-chatbubbles,.ivu-icon-ios-checkmark,.ivu-icon-md-checkmark-circle-outline,.ivu-icon-ios-clock,.ivu-icon-ios-close-circle,.ivu-icon-ios-bus,
.ivu-icon-md-closed-captioning,.ivu-icon-ios-cloud-circle-outline,.ivu-icon-ios-cloud-download,.ivu-icon-ios-cloud-upload-outline,.ivu-icon-md-construct,
.ivu-icon-ios-color-palette-outline,.ivu-icon-ios-code-download,.ivu-icon-ios-cart-outline,.ivu-icon-ios-contacts-outline,.ivu-icon-ios-create-outline,
.ivu-icon-ios-book-outline,.ivu-icon-md-contrast,.ivu-icon-md-download,.ivu-icon-md-easel,.ivu-icon-ios-exit,.ivu-icon-ios-eye,.ivu-icon-md-document,
.ivu-icon-md-eye-off,.ivu-icon-ios-female,.ivu-icon-ios-film,.ivu-icon-ios-flag,.ivu-icon-md-flame,.ivu-icon-ios-flask-outline,.ivu-icon-ios-git-branch,
.ivu-icon-ios-folder,.ivu-icon-md-folder-open,.ivu-icon-logo-freebsd-devil,.ivu-icon-ios-game-controller-a-outline,.ivu-icon-ios-disc,.ivu-icon-md-body,
.ivu-icon-md-git-compare,.ivu-icon-ios-git-pull-request,.ivu-icon-md-glasses,.ivu-icon-logo-googleplus,.ivu-icon-ios-hammer,.ivu-icon-ios-images-outline,
.ivu-icon-ios-headset-outline,.ivu-icon-md-heart-outline,.ivu-icon-md-help-buoy,.ivu-icon-ios-home-outline,.ivu-icon-md-ice-cream,.ivu-icon-logo-instagram,
.ivu-icon-md-hand,.ivu-icon-ios-information,.ivu-icon-ios-ionitron-outline,.ivu-icon-md-jet,.ivu-icon-ios-keypad-outline,.ivu-icon-ios-musical-notes-outline,
.ivu-icon-ios-map,.ivu-icon-ios-medal-outline,.ivu-icon-ios-medkit,.ivu-icon-md-megaphone,.ivu-icon-ios-microphone,.ivu-icon-md-moon,.ivu-icon-md-log-out,
.ivu-icon-ios-leaf-outline,.ivu-icon-logo-linkedin,.ivu-icon-md-list-box,.ivu-icon-ios-lock-outline,.ivu-icon-ios-mail-outline,.ivu-icon-ios-mic-outline,
.ivu-icon-md-move,.ivu-icon-ios-no-smoking,.ivu-icon-ios-notifications-outline,.ivu-icon-md-notifications-outline,.ivu-icon-ios-male,.ivu-icon-md-pizza,
.ivu-icon-ios-nutrition-outline,.ivu-icon-md-open,.ivu-icon-ios-outlet-outline,.ivu-icon-ios-paper-plane,.ivu-icon-md-partly-sunny,.ivu-icon-ios-person,
.ivu-icon-ios-planet-outline,.ivu-icon-logo-playstation,.ivu-icon-ios-power-outline,.ivu-icon-ios-pricetags,.ivu-icon-md-print,.ivu-icon-ios-qr-scanner,
.ivu-icon-md-person-add,.ivu-icon-ios-photos,.ivu-icon-md-pie,.ivu-icon-ios-pint-outline,.ivu-icon-ios-paw-outline,.ivu-icon-ios-remove-circle-outline,
.ivu-icon-ios-radio,.ivu-icon-ios-radio-button-on,.ivu-icon-ios-recording,.ivu-icon-ios-redo-outline,.ivu-icon-ios-square-outline,.ivu-icon-ios-trending-down,
.ivu-icon-md-repeat,.ivu-icon-md-restaurant,.ivu-icon-ios-reverse-camera,.ivu-icon-md-rewind,.ivu-icon-ios-rose-outline,.ivu-icon-ios-refresh-circle-outline,
.ivu-icon-md-send,.ivu-icon-ios-share-outline,.ivu-icon-ios-shirt,.ivu-icon-ios-skip-backward,.ivu-icon-md-skip-forward,.ivu-icon-md-snow,.ivu-icon-ios-search,
.ivu-icon-md-star,.ivu-icon-ios-stats-outline,.ivu-icon-md-stopwatch,.ivu-icon-ios-sunny-outline,.ivu-icon-ios-switch-outline,.ivu-icon-md-tablet-landscape,
.ivu-icon-ios-thermometer-outline,.ivu-icon-ios-thumbs-up,.ivu-icon-md-thunderstorm,.ivu-icon-ios-timer-outline,.ivu-icon-ios-transgender,.ivu-icon-md-sad,
.ivu-icon-ios-trophy-outline,.ivu-icon-logo-twitter,.ivu-icon-ios-undo-outline,.ivu-icon-logo-usd,.ivu-icon-ios-volume-down,.ivu-icon-md-volume-off,
.ivu-icon-ios-warning,.ivu-icon-ios-water,.ivu-icon-ios-wifi-outline,.ivu-icon-md-wine,.ivu-icon-logo-xbox,.ivu-icon-md-tennisball{
  color: #CE7BF9;
}
</style>
