<i18n src="./../../../locales/general.yaml"></i18n>

<template>
  <div class="container">
    <!-- <figure class="image is-2by1">
      <img src="" alt="" style="background-color: whitesmoke">
    </figure> -->
    <div class="columns">
      <div class="column">
        <h1 class="title is-1">
          {{ $t('ullim-hall', language) }}
        </h1>
        <p>
          이것이야말로 하여도 심장의 오직 가슴이 그러므로 두손을 아름다우냐? 보내는 이상을 그들의 이것은 같은 설산에서 보이는 웅대한 유소년에게서 칼이다. 청춘 이상이 대한 못할 튼튼하며, 것이다. 가지에 놀이 만물은 보라. 생의 할지니, 우리 이 간에 곳이 트고, 봄바람이다. 고동을 무한한 피고, 심장은 앞이 쓸쓸하랴? 옷을 것이 우리는 그들의 너의 대한 뿐이다. 우리 피에 열매를 천지는 있다. 갑 동력은 타오르고 수 싸인 용감하고 구할 말이다. 생생하며, 얼마나 소담스러운 노래하며 물방아 생명을 그리하였는가? 우리의 가진 그들의 이상이 같지 얼마나 피어나기 행복스럽고 우리 봄바람이다.
        </p>
        <p>얼마나 인류의 희망의 듣기만 어디 예수는 속에서 곳으로 말이다. 가진 끓는 새가 풀밭에 할지니, 우리 운다. 청춘 피고, 피어나기 어디 되려니와, 따뜻한 구하기 그들의 아니다. 인류의 밥을 품고 소담스러운 붙잡아 같지 온갖 위하여서. 우리 피고 방황하여도, 그들의 내려온 곳으로 싸인 지혜는 것은 것이다. 싶이 품으며, 얼마나 구할 시들어 설레는 대고, 그림자는 것이다.보라, 위하여서. 못할 인생을 방지하는 광야에서 부패뿐이다. 그와 꽃이 생명을 천고에 가장 있는 인간의 우리의 뿐이다. 우리의 때에, 있는 발휘하기 청춘의 청춘의 그와 작고 이상이 운다. 인생에 미묘한 만물은 때에, 능히 청춘의 청춘은 쓸쓸한 아니다.</p>
        <p>광야에서 대고, 불어 옷을 쓸쓸하랴? 듣기만 가지에 만천하의 피다. 있으며, 이성은 장식하는 얼마나 봄바람이다. 없으면 많이 붙잡아 예수는 그들의 만물은 가치를 위하여, 심장의 아름다우냐? 곧 곳이 없으면 하는 풀밭에 우리 가치를 힘있다. 때에, 것은 더운지라 심장은 청춘의 예수는 아름답고 고동을 이성은 듣는다. 사랑의 같이, 피어나는 수 것이다.보라, 때문이다. 않는 내는 가치를 피어나기 우리 있는 커다란 운다. 사랑의 불어 것은 이상의 찾아다녀도, 그리하였는가? 살 희망의 풀이 사는가 보내는 사라지지 피에 원대하고, 그들은 피다. 그와 얼마나 바로 그들은 몸이 우리의 맺어, 열락의 할지니, 황금시대다.</p>
      </div>
      <div class="column"></div>
    </div>
  </div>
</template>

<script>
import { mapState } from 'vuex'

export default {
  name: 'intro-ullim-hall',
  metaInfo () {
    return {
      title: this.$t('ullim-hall', this.language)
    }
  },
  computed: {
    ...mapState(['language'])
  }
}
</script>

<style scoped>
h1.title.is-1 {
  font-family: 'Kopub Batang';
  margin-top: 3rem;
}
p {
  margin-bottom: 1rem;
}
</style>