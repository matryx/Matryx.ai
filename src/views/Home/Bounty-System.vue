<template>
  <section class="bkg--blue-gradient" id="bounty-system">
    <div class="content-container content-container--large text-color--white">
      <!--
      <h2 class="title content-container--medium">
        <span v-if=" language === 'ru' ">Стимулирование инноваций посредством конкурса в духе сотрудничества</span>
      	<span v-else-if=" language === 'ch' ">通过合作竞争激励创新</span>
      	<span v-else-if=" language === 'ge' ">Innovationsanreize durch kollaborativen Wettbewerb</span>
      	<span v-else-if=" language === 'ja' ">コラボレーションによる競争を通じてイノベーションを奨励</span>
      	<span v-else-if=" language === 'ko' ">협업적 경쟁을 통한 보상형 혁신</span>
      	<span v-else>Incentivized Innovation Through Collaborative Competition</span>
      </h2>
      <p class="content-container--medium">
        <span v-if=" language === 'ru' ">Система вознаграждений Matryx призвана ускорить процесс инноваций и вознаградить всех пользователей, которые вносят свой вклад. Вознаграждение — это просто задача, опубликованная на платформе со справедливым вознаграждением MTX для пользователей, которые вносят вклад в ответ. Любой пользователь может разместить вознаграждение для сообщества Matryx и принять участие в решении задачи.</span>
				<span v-else-if=" language === 'ch' ">Matryx 赏金制度旨在加速创新并奖励所有作出贡献的用户。赏金只是一个被发布到平台的挑战，对促成答案的用户给予公平的 MTX 奖励。任何用户均可发布赏金到 Matryx 社区，任何用户均可参与。</span>
				<span v-else-if=" language === 'ge' ">Ziel des Bounty-Systems von Matryx ist es, Innovation zu beschleunigen und alle mitwirkenden Nutzer zu belohnen. Eine Belohnung ist schlichtweg eine auf der Plattform gepostete Aufgabe mitsamt einer fairen MTX-Vergütung für Nutzer, die zur Lösung beitragen. Jeder Nutzer kann Belohnungen in der Matryx-Community posten und jeder Nutzer kann teilnehmen.</span>
				<span v-else-if=" language === 'ja' ">Matryxの報奨システムは、イノベーションを加速し、貢献するすべてのユーザーに報酬を与えることを目指しています。報奨金は、答えに貢献するユーザーに対し、公平なMTX報酬でプラットフォームに掲示された挑戦でしかありません。どのユーザーもMatryxコミュニティに報奨金を掲示でき、どのユーザーでも参加できます。</span>
				<span v-else-if=" language === 'ko' ">Matryx 포상 제도는 더 빠른 혁신은 물론 기여한 모든 이용자들에게 보상해주는 것을 목적으로 하고 있습니다. 포상금이란 간단히 말해서 해결책에 기여를 한 이용자들을 위한 적절한 액수의 MTX 보상과 함께 플랫폼 상에서 게시된 챌린지를 지칭합니다. 이용자 중 누구라도 Matryx 커뮤니티에서 포상금을 게시할 수 있으며 이용자 중 누구라도 참여할 수 있습니다.</span>
				<span v-else>The Matryx Bounty system aims to accelerate innovation and reward all users who contribute.
        A bounty is simply a challenge posted to the platform with a fair MTX reward for users who contribute
        to the answer. Any user can post bounties to the Matryx community and any user can participate.</span>
      </p>-->
      <h4 class="text-align-center white">
        <span v-if=" language === 'ru' ">Как это работает</span>
        <span v-else-if=" language === 'ch' ">如何运作</span>
        <span v-else-if=" language === 'ge' ">So funktioniert's</span>
        <span v-else-if=" language === 'ja' ">プロセス</span>
        <span v-else-if=" language === 'ko' ">이용방법</span>
        <span v-else-if=" language === 'es' ">Cómo Funciona</span>
        <h2 v-else>How it Works</h2>
      </h4>
      <h5>
        <span v-if=" language === 'ru' ">Пример</span>
        <span v-else-if=" language === 'ch' ">例子</span>
        <span v-else-if=" language === 'ge' ">Beispiele</span>
        <span v-else-if=" language === 'ja' ">例</span>
        <span v-else-if=" language === 'ko' ">본보기</span>
        <span v-else-if=" language === 'es' ">Ejemplo</span>
        <span v-else>Example</span>
      </h5>
      <div class="how_it_works_details">
      <p>
        <span v-if=" language === 'ch' ">Matryx平台的工作流程是这样的，让我们假设一个虚拟的公司Marshal Aviations在寻求开发一种能够飞行很长时间的航天器，并愿意为此投入10万mtx的开发预算。利用nanome设计套件和工具，matryx社区的工程师、开发人员、工业设计师等等来协作竞争解决这个问题。
        <br/><br/>
        为了简单起见，我们假设参与者数量很少，并且在两轮竞标赛后找到一个解决档案。虽然实际上Matryx可以进行大规模的协作，并可以在同一个时间点内有多个开发周期。
        </span>
        <span v-else-if=" language === 'es' ">Para ilustrar el flujo de trabajo de Matryx, supongamos que el <span class = "matryx-lighter-blue"> empresa ficticia </span> Marshal Aviations busca desarrollar una nave espacial para ir audazmente al infinito y más allá, y está dispuesto a dedicarle un generoso presupuesto de desarrollo de 100,000 MTX para este propósito. Utilizando la suite de diseño Nanome y las herramientas de su elección, la comunidad de desarrolladores, ingenieros y diseñadores industriales de Matryx ahora puede competir en colaboración para resolver el problema planteado.
        <br/><br/>
        Por simplicidad, supongamos que el número de participantes es mínimo y que después de dos rondas se encuentra una solución. En realidad, Matryx permite una colaboración masiva, que ocurre en paralelo y durante múltiples rondas de desarrollo.
        </span>
        <span v-else>
          To illustrate the Matryx workflow, let us assume that the <span class="matryx-lighter-blue">fictious company</span> Marshal Aviations seeks to develop a spacecraft to boldly go to infinity and beyond, and is willing to devote a generous development budget of 100,000 MTX for this purpose.
          Utilizing the Nanome design suite and tools of their choice, the Matryx community of developers, engineers and industrial designers can now collaboratively compete to solve the posed problem.
          <br/><br/>
          For simplicity’s sake, let us assume that the number of participants is minimal and that after two rounds a solution is found. In reality, Matryx enables massive collaboration, happening in parallel and during multiple development rounds.
        </span>
      </p>

        <div class="bounty__diagram">
          <h4>
            <span v-if=" language === 'ru' ">Начинается конкурс</span>
            <span v-else-if=" language === 'ch' ">比赛开始</span>
            <span v-else-if=" language === 'ge' ">Wettbewerb beginnt</span>
            <span v-else-if=" language === 'ja' ">競争開始</span>
            <span v-else-if=" language === 'ko' ">경쟁전이 시작됩니다</span>
            <span v-else-if=" language === 'es' ">COMPETICION COMIENZA</span>
            <span v-else>COMPETITION STARTS</span>
          </h4>
          <caption class="text-color--white ">
            <span v-if=" language === 'ru' ">Постройка космического корабля</span>
            <span v-else-if=" language === 'ch' ">建造一艘宇宙飞船</span>
            <span v-else-if=" language === 'ge' ">Bau eines Raumschiffs</span>
            <span v-else-if=" language === 'ja' ">宇宙探査機の作成</span>
            <span v-else-if=" language === 'ko' ">우주선을 만드세요</span>
            <span v-else-if=" language === 'es' ">BOUNTY: DISENAR UNA NAVE ESPECIAL</span>
            <span v-else>BOUNTY: DESIGN A SPACECRAFT</span>
          </caption>
          <img src="../../assets/images/bounty-drawing.svg" alt="">
        </div>
      </div>
      <div class="bounty">
        <div class="bounty__explanation">

          <div class="bounty__explanation__card">
            <div class="bounty__explanation__card__item">
              <span>1</span>
              <h4>
                <span v-if=" language === 'ru' ">Опубликовано вознаграждение</span>
        				<span v-else-if=" language === 'ch' ">发布赏金</span>
        				<span v-else-if=" language === 'ge' ">Belohnung wird gepostet</span>
        				<span v-else-if=" language === 'ja' ">報奨金が掲示される</span>
        				<span v-else-if=" language === 'ko' ">포상금이 게시됩니다</span>
                <span v-else-if=" language === 'es' ">Enviar problema / Publicar Bounty</span>
        				<span v-else>Submit Problem / Post Bounty</span>
              </h4>
              <p>
                <span v-if=" language === 'ru' ">Маршалл запрашивает 3D-модель космического корабля и размещает вознаграждение</span>
        				<span v-else-if=" language === 'ch' ">马歇尔请求设计 3D 宇宙飞船模型并发布赏金</span>
        				<span v-else-if=" language === 'ge' ">Marshall stellt eine Anfrage für ein 3D-Raumschiffmodell und postet eine Belohnung</span>
        				<span v-else-if=" language === 'ja' ">Marshallが3Dの宇宙探査機モデルを要求し、報奨金を掲示する</span>
        				<span v-else-if=" language === 'ko' ">Marshall이 3D 우주선 모델링을 게시하면서 포상금을 게시합니다</span>
                <span v-else-if=" language === 'es' ">Marshal Aviation solicita propuestas para un modelo de nave espacial 3D. Bounty de desarrollo: 100.000 MTX.</span>
        				<span v-else>Marshal Aviation requests proposals for a 3D Space craft model. Development bounty: 100,000 MTX</span>
              </p>
            </div>
            <div class="bounty__explanation__card__item">
              <span>2</span>
              <h4>
                <span v-if=" language === 'ru' ">Представлены модели</span>
        				<span v-else-if=" language === 'ch' ">提交设计</span>
        				<span v-else-if=" language === 'ge' ">Entwürfe werden eingereicht</span>
        				<span v-else-if=" language === 'ja' ">デザインが提出される</span>
        				<span v-else-if=" language === 'ko' ">디자인이 제출됩니다</span>
                <span v-else-if=" language === 'es' ">Pioneros e innovadores responden</span>
                <span v-else>Pioneers &#38; Innovators Respond</span>
              </h4>
              <p>
                <span v-if=" language === 'ru' ">Два пользователя представили свои лучшие модели космического корабля. Маршаллу нравится дизайн, и он запрашивает раунд пересмотра у сообщества.</span>
        				<span v-else-if=" language === 'ch' ">两位用户提交他们最好的宇宙飞船模型。马歇尔喜欢其中一个设计，请求matryx社区进行一轮修正。</span>
        				<span v-else-if=" language === 'ge' ">Zwei Nutzer reichen ihre besten Raumschiffmodelle ein. Marshall gefällt einer der Entwürfe und er bittet die Community um eine Überarbeitungsrunde.</span>
        				<span v-else-if=" language === 'ja' ">2人のユーザーが自己最高の宇宙探査機モデルを提出する。Marshallはその中の1つのデザインが気に入り、コミュニティからの改訂を要請する。</span>
        				<span v-else-if=" language === 'ko' ">2명의 이용자들이 자신들의 최고의 우주선 모델린 결과물을 제출합니다. Marshal은 그 중 마음에 드는 한가지 결과물을 커뮤니티에 1회의 수정을 요청합니다.</span>
                <span v-else-if=" language === 'es' ">Los primeros diseñadores / desarrolladores / entusiastas presentan sus mejores modelos de naves espaciales.</span>
        				<span v-else>First designers/developers/enthusiasts submit their best Spacecraft models. </span>
              </p>
            </div>
            <div class="bounty__explanation__card__item">
              <span>3</span>
              <h4>
                <span v-if=" language === 'ru' ">Выбран победитель</span>
        				<span v-else-if=" language === 'ch' ">选择获胜者</span>
        				<span v-else-if=" language === 'ge' ">Sieger wird ausgewählt</span>
        				<span v-else-if=" language === 'ja' ">勝者が選ばれる</span>
        				<span v-else-if=" language === 'ko' ">우승자가 선정됩니다</span>
                <span v-else-if=" language === 'es' ">Los primeros ganadores son elegidos</span>
        				<span v-else>First winners are chosen</span>
              </h4>
              <p>
                <span v-if=" language === 'ru' ">Два новых пользователя берут предпочтительные дизайны Маршалла и выполняют их «ремикс». Маршалл выбирает победителя и смарт-контракт распределяет MTX среди всех соавторов.</span>
        				<span v-else-if=" language === 'ch' ">两位新用户采用马歇尔最喜爱的设计并进行整合与改进。马歇尔选择一个获胜者，同时智能合同将 MTX 分配给所有贡献者。</span>
        				<span v-else-if=" language === 'ge' ">Zwei neue Nutzer greifen Marshalls favorisierten Entwurf auf und erstellen daraus jeweils einen „Remix”. Marshall wählt einen Sieger aus und ein Smart Contract verteilt MTX an alle Mitwirkenden.</span>
        				<span v-else-if=" language === 'ja' ">2人の新しいユーザーがMarshallが気に入ったデザインを使い、それをリミックスする。マーシャルは勝者を選び、スマートコントラクトがMTXをすべての寄稿者に配布する。</span>
        				<span v-else-if=" language === 'ko' ">2명의 새로운 이용자들이 Marshall의 마음에 드는 디자인을 가지고 재변형 작업을 합니다. Marshall은 우승자를 선정하고 스마트 계약은 MTX를 모든 기여자들에게 배분합니다.</span>
                <span v-else-if=" language === 'es' ">Marshal elige los diseños más cercanos a sus expectativas y solicita mejoras adicionales.</span>
        				<span v-else>Marshal chooses designs that are closest to their expectations and requests further improvements.</span>
              </p>
            </div>
            <div class="bounty__explanation__card__item">
              <span>4</span>
              <h4>
                <span v-if=" language === 'ru' ">Выбран победитель</span>
        				<span v-else-if=" language === 'ch' ">选择获胜者</span>
        				<span v-else-if=" language === 'ge' ">Sieger wird ausgewählt</span>
        				<span v-else-if=" language === 'ja' ">勝者が選ばれる</span>
        				<span v-else-if=" language === 'ko' ">우승자가 선정됩니다</span>
                <span v-else-if=" language === 'es' ">Revisión y revisión por pares</span>
        				<span v-else>Peer Review &#38; Improvement</span>
              </h4>
              <p>
                <span v-if=" language === 'ru' ">Два новых пользователя берут предпочтительные дизайны Маршалла и выполняют их «ремикс». Маршалл выбирает победителя и смарт-контракт распределяет MTX среди всех соавторов.</span>
        				<span v-else-if=" language === 'ch' ">两位新用户采用马歇尔最喜爱的设计并进行整合与改进。马歇尔选择一个获胜者，同时智能合同将 MTX 分配给所有贡献者。</span>
        				<span v-else-if=" language === 'ge' ">Zwei neue Nutzer greifen Marshalls favorisierten Entwurf auf und erstellen daraus jeweils einen „Remix”. Marshall wählt einen Sieger aus und ein Smart Contract verteilt MTX an alle Mitwirkenden.</span>
        				<span v-else-if=" language === 'ja' ">2人の新しいユーザーがMarshallが気に入ったデザインを使い、それをリミックスする。マーシャルは勝者を選び、スマートコントラクトがMTXをすべての寄稿者に配布する。</span>
        				<span v-else-if=" language === 'ko' ">2명의 새로운 이용자들이 Marshall의 마음에 드는 디자인을 가지고 재변형 작업을 합니다. Marshall은 우승자를 선정하고 스마트 계약은 MTX를 모든 기여자들에게 배분합니다.</span>
                <span v-else-if=" language === 'es' ">Los nuevos usuarios toman los diseños favoritos de Marshall y los 'remezclan'. Se agregan nuevas ideas y se vuelven a usar las antiguas. Cada paso es validado por el resto de la comunidad.</span>
        				<span v-else>New users take Marshall's favorite designs and 'remix' them. New ideas are added and old ones reused. Every step is validated by the rest of the community.</span>
              </p>
            </div>
            <div class="bounty__explanation__card__item">
              <span>5</span>
              <h4>
                <span v-if=" language === 'ru' ">Выбран победитель</span>
        				<span v-else-if=" language === 'ch' ">选择获胜者</span>
        				<span v-else-if=" language === 'ge' ">Sieger wird ausgewählt</span>
        				<span v-else-if=" language === 'ja' ">勝者が選ばれる</span>
        				<span v-else-if=" language === 'ko' ">우승자가 선정됩니다</span>
                <span v-else-if=" language === 'es' ">El ganador es escojido</span>
        				<span v-else>Winner is Chosen</span>
              </h4>
              <p>
                <span v-if=" language === 'ru' ">Два новых пользователя берут предпочтительные дизайны Маршалла и выполняют их «ремикс». Маршалл выбирает победителя и смарт-контракт распределяет MTX среди всех соавторов.</span>
        				<span v-else-if=" language === 'ch' ">两位新用户采用马歇尔最喜爱的设计并进行整合与改进。马歇尔选择一个获胜者，同时智能合同将 MTX 分配给所有贡献者。</span>
        				<span v-else-if=" language === 'ge' ">Zwei neue Nutzer greifen Marshalls favorisierten Entwurf auf und erstellen daraus jeweils einen „Remix”. Marshall wählt einen Sieger aus und ein Smart Contract verteilt MTX an alle Mitwirkenden.</span>
        				<span v-else-if=" language === 'ja' ">2人の新しいユーザーがMarshallが気に入ったデザインを使い、それをリミックスする。マーシャルは勝者を選び、スマートコントラクトがMTXをすべての寄稿者に配布する。</span>
        				<span v-else-if=" language === 'ko' ">2명의 새로운 이용자들이 Marshall의 마음에 드는 디자인을 가지고 재변형 작업을 합니다. Marshall은 우승자를 선정하고 스마트 계약은 MTX를 모든 기여자들에게 배분합니다.</span>
                <span v-else-if=" language === 'es' ">Marshall escoje un ganador y el cotrato intelligente distribuye MTX a todos los contribuyentes y validadores</span>
        				<span v-else>Marshall chooses a winner and a smart contract distributes MTX to all contributors and validators. </span>
              </p>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'BountySystem',
  computed: {
    language () {
      return this.$store.state.language
    }
  }
}
</script>

<style lang="scss" scoped>
#bounty-system {
  /*padding: 20px 0 ;*/
}

.how_it_works_details{
  width: 50%;
  /*max-width: 400px;*/
  display: -webkit-inline-box;
    p{
    font-size: 18px;
    line-height: 28px;
    padding-top: 25px;
    padding-right: 25px;
  }
}

.text-align-center{
  text-align: center;
}

h2, h5, p, caption {
  opacity: 0.8;
}

.title {
  margin-bottom: 20px;
  max-width: 550px;
  font-size: 28px;
  line-height: 40px;
}

.bkg--blue-gradient {
  background-color: #0F3249;
  // background-image: url('../../assets/images/backgrounds/bluegradient.svg');
  background-size:cover;
  background-repeat: no-repeat;
  background-position:bottom;
}

p.content-container--medium {
  max-width: 750px;
  font-size: 18px;
}

.white-bkg {
    margin: -50px 0;
}
.bounty {
  display:-webkit-box;display:-ms-flexbox;display:flex;
  justify-content: space-between;
  margin: 40px 0;

 &__diagram {
    flex: 1 1 auto;
    padding-top: 20px;
    max-width: 500px;

   h4, caption {
      width: 100%;
      text-align:center;
      font-size: 20px;
    }
    caption{
      display: block;
      padding-top: 0;
      margin-bottom: 20px;
      font-size: 14px;
    }
    img {
      width: 100%;
    }
  }

 &__explanation{
    padding-top: 20px;
    /*width: 50%;*/
    /*max-width: 400px;*/
    margin-right: 80px;
    position:relative;

   & > h4 {
      opacity: 0.8;
      font-size:22px;
      margin-bottom: 20px;
    }

   &__card {
      border: 1px solid rgba(255,255, 255,0.3);
      padding: 20px;

     &__item {
        & > span {
          display:inline-block;
          vertical-align: top;
          font-size: 18px;
        }
        h4 {
          display: inline-block;
          width: calc(100% - 70px);
          margin-left: 20px;
          margin-top: -2px;

         &::after {
            content: '';
            clear: both;
          }

         span {
            font-size: 16px;
            display:block;
            opacity: 0.8;
          }
        }
        p {
            width: calc(100% - 70px);
            margin-left: 30px;
            font-size: 16px;
            display:block;
            opacity: 0.8;
         }
      }
    }
  }
}


/*----- MEDIA QUERIES -----*/
@media screen and (max-width: 900px) {
  .content-container {
    padding-bottom: 0;
  }

  .how_it_works_details{
    width: 100%;
    display: block;
  }
  .bounty {
    flex-direction: column;

   & > * {
      width: 100%;
      max-width: 100%;
    }

   &__explanation__card {
      margin-bottom: 40px;
    }
    &__diagram img {
      max-width: 500px;
      margin: 0 auto;
      text-align: center;
      display: block;
    }
  }
}

</style>
