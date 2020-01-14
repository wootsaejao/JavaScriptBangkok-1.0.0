<template>
  <div class="sponsors-wrapper">
    <div class="sponsors-group">
      <img src="./sponsors-svg/platinum/kbtg.svg" alt="KBTG" height="130" />
    </div>

    <div class="sponsors-group sponsors-tier2">
      <img
        class="oozou"
        src="./sponsors-svg/gold/oozou.svg"
        alt="OOZOU"
        height="32"
      />
      <img
        class="exxonmobil"
        src="./sponsors-svg/gold/exxonmobil.svg"
        alt="ExxonMobil"
        height="38"
      />
      <img
        class="odds"
        src="./sponsors-svg/gold/odds.svg"
        alt="ODDS"
        height="40"
      />
    </div>

    <div class="sponsors-group sponsors-tier3 pt-15">
      <img
        class="nextzy"
        src="./sponsors-svg/silver/nextzy.svg"
        alt="Nextzy"
      />
      <img
        class="nextmo"
        src="./sponsors-svg/silver/nextmo.svg"
        alt="NEXMO"
      />
      <img
        class="appman"
        src="./sponsors-svg/silver/appman.svg"
        alt="APPMAN"
      />
    </div>

    <div class="sponsors-group sponsors-tier3 pt-15">
      <img
        class="nexthop"
        src="./sponsors-svg/silver/nexthop.svg"
        alt="next hop"
      />
      <img
        class="eventpop"
        src="./sponsors-svg/silver/eventpop.svg"
        alt="Eventpop"
      />
      <img
        class="hotnow"
        src="./sponsors-svg/silver/hotnow.svg"
        alt="HOTNOW"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'SponsorList',
}
</script>

<style scoped>
.sponsors-group {
  display: flex;
  justify-content: center;
  align-items: center;
}
.sponsors-group > img {
  padding-left: 10px;
  padding-right: 10px;
}

.sponsors-tier2 {
  flex-direction: column;
  padding-top: 15px;
  padding-bottom: 15px;
}
.sponsors-tier2 > img {
  padding-top: 30px;
}
.sponsors-tier2 > .exxonmobil {
  padding-top: 38px;
}

.sponsors-tier3 > img {
  max-width: 100%;
  height: auto;
}
.sponsors-tier3 > .nextmo {
  height: 23px;
}
.sponsors-tier3 > .nexthop {
  height: 23px;
}

@media (min-width: 795px) {
  .sponsors-group > img {
    padding-left: 25px;
    padding-right: 25px;
  }

  .sponsors-tier2 {
    flex-direction: row;
    padding-top: 50px;
  }
  .sponsors-tier2 > img {
    padding-top: 0;
  }
  .sponsors-tier2 > .oozou {
    height: 42px;
  }
  .sponsors-tier2 > .exxonmobil {
    padding-top: 0;
    height: 53px;
  }
  .sponsors-tier2 > .odds {
    height: 43px;
  }

  .sponsors-tier3 > .nextzy {
    height: 42px;
  }
  .sponsors-tier3 > .nextmo {
    height: 45px;
  }
  .sponsors-tier3 > .appman {
    height: 73px;
  }
  .sponsors-tier3 > .nexthop {
    height: 40px;
  }
  .sponsors-tier3 > .eventpop {
    height: 30px;
  }
  .sponsors-tier3 > .hotnow {
    height: 38px;
  }
}

.pt-15 {
  padding-top: 15px;
}
</style>
