<template lang="pug">
PageBook(:showAuthor="false")
  p 
    em Den eldre Edda 
    | er betegnelsen på de aller eldste skriftene fra norrøn litteratur. Ordet «edda» betyr oldemor og indikerer at vi har med gammel diktning å gjøre. 

  p 
    em Den eldre Edda 
    | er en samling helte- og gudedikt (om lag 30) som ble funnet på Island i 1643. Ingen av eddadiktene er signert av navngitte forfattere. 

  p Det er vanlig å dele eddadiktene i to grupper: gudedikt og heltedikt. 

  p Eddadiktene forteller om gamle ­dager. Forskerne tror at mange eddadikt kan være skrevet i Norge, men de er nedskrevet på Island. 

  p Stoffet i eddadiktene er først og fremst hentet fra mytene, det vil si den norrøne mytologien. Gudene i den norrøne mytologien står sentralt i eddadiktene, og diktene forteller oss at menneskene på den tida hadde et enkelt forhold til Odin og Tor. Du kan lese om den norrøne mytologien et annet sted i Tidslinja. 

  p De tre mest kjente diktene fra 
    em Den eldre Edda 
    | er «Voluspå», «Trymskvida» og «Håvamål». 


  ImageTextBlock.mt5(
    :image="require(`./Edda_Faeroeyene.jpg`)"
    :imageColumns="4"
    imageCaption="Her er volva framstilt på et frimerke fra Færøyene."
    altText="Frimerke med teksten Føroyar. Kappekledd kvinne omgitt av ornamental skog. Illustrasjon"
    )    
    h3 «Voluspå» 
    p «Voluspå» er et gudedikt om jordas skapelse, hva som fører til jordas undergang, og om selve undergangen, det såkalte 
      em ragnarok
      | . Det er en spåkvinne (volve) som snakker til oss gjennom diktet. 

  
  ImageTextBlock.mt5(
    :image="require(`./Edda_Tor_strir_med_jotnene.jpg`)"
    :imageColumns="4"
    altText="Rødkledd kriger i vogn trukket av to geiter løfter en hammer. Lynet slår ned i fiendene han sloss mot. Maleri"
    )
    template(v-slot:caption)
      em Tor strir med jotnene. 
      | Maleri av Mårten Eskil Winge

    h3 «Trymskvida»
    p «Trymskvida» er et gudedikt som handler om jotnen Trym som stjeler hammeren til Tor. Tor må ha hjelp av den listige Loke for å få tilbake hammeren. Hammeren er både et forsvarsvåpen og et fruktbarhetssymbol for æsene, derfor er det svært viktig for Tor å få den tilbake. Men selv om gudene altså må løse et alvorlig problem, er handlingen skildret med mye humor. 
  
  figure.col.col6.right-image.mt5
    img(src="./Edda_Haavamaal.jpg" alt="Kriger med skjegg og sverd står foran dør som er dekorert med treskjæring. Teksten Håvamål er del av bildet. Illustrasjon")

  h3 «Håvamål» 
  p «Håvamål» betyr «den høyes tale», det vil si at det er Odin som taler. «Håvamål» er på mange måter et læredikt, og det er Odin som gir råd og livsvisdom til menneskene i et samfunn fylt av fiendskap og farer. 

  p Rådene vi får gjennom «Håvamål», kan fortone seg kyniske. Det gjelder ikke bare å være en lojal og god venn, en skal også være listig og lur. Det er viktig å stole på egen dømmekraft i et samfunn med mange farer. Å stole på andre er det bare tosker som gjør. Diktene formidler en hedensk nyttemoral. 

  p Det er 80 strofer i «Håvamål». Hver strofe har seks linjer som er bundet sammen med bokstavrim (allitterasjon). 

  blockquote
    | Vatn og handduk
    br
    | han ventar å få,
    br
    | når til bords han vert beden.
    br
    | Syn godlaget fram,
    br
    | så greileg du kan,
    br
    | med ord og attbeding.

  NdlaAudio(source="media/books/edda/Haavamål_strofe_68-72_og_74-77.mp3")
  p 
    | Les 
    a(:href="globalVars.publicPath + 'media/books/edda/haavamaal.html'" target="_blank") utdrag 
    | fra Håvamål

  h3 Heltedikt 
  p Heltediktene i 
    em Den eldre Edda 
    | forteller sagn som har røtter helt tilbake i folkevandringstida. Diktene levde på folkemunne i mange hundre år før de ble nedskrevet. Flere av heltegjerningene har overmenneskelige dimensjoner. Heltene kjemper både mot ytre farer og mot sin indre samvittighet. 

  p Ett av heltediktene i Den eldre Edda forteller om Sigurd Fåvnesbane. Dette sagnet går igjen i hele det germanske språkområdet, blant annet i det tyske heltediktet «Nibelungenlied». 

  p Sigurd blir oppfostret av dvergen Regin. I diktet «Reginsmål» får vi høre om skatten som draken Fåvne vokter over. Fåvne er bror til Regin, og skatten er arven etter faren deres, Reidmar. Men Fåvne nekter å dele med bror sin. Da egger Regin Sigurd til å drepe Fåvne. Han smir om sverdet Gram, som Sigurd har arvet etter faren. Med dette sverdet skal han kjempe mot draken.

  figure.col.col3.left-image
    img(src="./Den-eldre-Edda_Utsnitt-fra-treskjering-Hylestad-stavkirke.jpg" alt="Treskjæring. Kriger med sverd og skjold slåss mot dragelignende uhyre. Foto")
    figcaption På Hylestad stavkirke er sagnet om Sigurd fremstilt.

  p «Fåvnesmål» forteller hvordan det går til når Sigurd dreper Fåvne. Før Fåvne dør, råder han Sigurd til å dra hjem uten skatten fordi gullet kommer til å bli hans bane. Dessuten advarer han Sigurd mot Regin. 

  p Etter at Fåvne er død, vil Regin ete hjertet til Fåvne. Han ber Sigurd steike Fåvnes hjerte over et bål. Sigurd tar på hjertet for å kjenne om det er fullsteikt. Da brenner han seg, stikker fingeren i munnen og får Fåvnes hjerteblod på tunga. Nå kan han forstå fuglemål. Fuglene forteller at Regin planlegger å svike han. Da dreper han Regin, tar med seg mye gull fra Fåvnes bol og rir deretter av gårde.  


  p.flex.flex-wrap
    .col.col6.p5
      h5 Norrøn tekst 
      p Sigurðr kvað: «Ráð er þér ráðit, en ek ríða mun til þess gulls, er í lyngvi liggr, en þú, Fáfnir, ligg í fjörbrotum, þar er þik hel hafi.» 
    .col.col6.p5
      h5 Oversettelse
      p Sigurd kvad: «Råd du meg rådde, men ride eg vil til gull som i lyngi ligg; men du, Fåvne, heve helorann fengi, til Hel deg heim fører.» 

  p.flex.flex-wrap
    .col.col6.p5
      h5 Norrøn tekst
      p Fáfnir kvað: «Reginn mik réð, hann þik ráða mun, hann mun okkr verða báðum at bana; fjör sitt láa, hygg ek, at Fáfnir myni; þitt varð nú meira megin.» 
    .col.col6.p5
      h5 Oversettelse
      p Fåvne kvad: «Meg svikråd gav Regin, han svikråd gav deg med, han vert oss båe til bane; livet lata lyt no Fåvne, meisteren min du vart.» 

  p Oversatt av Ivar Mortensson-Egnund, 1928 Kilde: 
    a(href="https://www.heimskringla.no" target="_blank") www.heimskringla.no

//  Medieinnhold: Beholde bildene. Lydspor ikke nødvendig på brødtekst, men om vi har opplesing av verset fra Håvamål er det fint om det er med

</template>

<script>
import PageBook from "@/components/PageBook";
import NdlaVideo from "@/components/NdlaVideo";
import NdlaAudio from "@/components/NdlaAudio";
import ImageTextBlock from "@/components/ImageTextBlock";

export default {
  name: "Book",
  inject: ["globalVars"],
  components: {
    ImageTextBlock,
    NdlaAudio,
    NdlaVideo,
    PageBook,
  },
  // data() {
  //   return {
  //     publicPath: process.env.BASE_URL,
  //   };
  // },
};
</script>

<style lang="scss" scoped></style>
