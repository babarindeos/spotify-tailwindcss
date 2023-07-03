<script setup></script>

<template>
  <div class="flex flex-col h-screen text-sm text-gray-400">
    <div class="bg-blue-500 flex flex-1 overflow-y-hidden">
      <div
        class="sidebar bg-gray-900-spotify w-48 flex flex-col flex-none justify-between font-semibold"
      >
        <ul class="py-6">
            <li class="border-l-4 border-green-600">
                    <a class="mx-4 mt-4 flex items-center group">                       
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5}  
                            stroke="currentColor" class="w-6 h-6 text-white group-hover:text-white fill-current">
                                <path strokeLinecap="round" strokeLinejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                            </svg>                       
                        <span class="ml-2 text-white group-hover:text-white">Home</span>
                    </a>
            </li>        

            <li class="border-l-4 border-gray-900">
                    <a class="mx-4 mt-2 flex items-center group">                       
                              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 group-hover:text-white">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 17.25v3.375c0 .621-.504 1.125-1.125 1.125h-9.75a1.125 1.125 0 01-1.125-1.125V7.875c0-.621.504-1.125 1.125-1.125H6.75a9.06 9.06 0 011.5.124m7.5 10.376h3.375c.621 0 1.125-.504 1.125-1.125V11.25c0-4.46-3.243-8.161-7.5-8.876a9.06 9.06 0 00-1.5-.124H9.375c-.621 0-1.125.504-1.125 1.125v3.5m7.5 10.375H9.375a1.125 1.125 0 01-1.125-1.125v-9.25m12 6.625v-1.875a3.375 3.375 0 00-3.375-3.375h-1.5a1.125 1.125 0 01-1.125-1.125v-1.5a3.375 3.375 0 00-3.375-3.375H9.75" />
                              </svg>
                 
                        <span class="ml-2 group-hover:text-white">Browse</span>
                    </a>
            </li>            
        </ul>
        <div class="sidebar-spotify overflow-y-auto px-5 mt-2">
            <h3 class="uppercase tracking-widest text-xs text-gray-500 font-normal">Campaign</h3>
            <ul class="leading-extra-loose mb-4">
                    <li class="truncate"><a href="#" class="hover:text-white">All Campaigns</a></li>
                    <li class="truncate"><a href="#" class="hover:text-white">Search Campaign</a></li>
            </ul>



            <h3 class="uppercase tracking-widest text-xs text-gray-500 font-normal">your library</h3>
            <ul class="leading-extra-loose mb-4">
                <li class="truncate"><a href="#" class="hover:text-white">Made For You</a></li>
                <li class="truncate"><a href="#" class="hover:text-white">Recently Played</a></li>
                <li class="truncate"><a href="#" class="hover:text-white">Liked Songs</a></li>
                <li class="truncate"><a href="#" class="hover:text-white">Albums</a></li>
                <li class="truncate"><a href="#" class="hover:text-white">Artists</a></li>
                <li class="truncate"><a href="#" class="hover:text-white">Podcasts</a></li>
            </ul>

            <h3 class="uppercase tracking-widest text-xs text-gray-500 font-normal">Playlists</h3>
            <ul class="leading-extra-loose">
                <li class="truncate"><a href="#" class="hover:text-white">Afrobeat Hits</a></li>
                <li class="truncate"><a href="#" class="hover:text-white">Afrobeat Covers</a></li>
                <li class="truncate"><a href="#" class="hover:text-white">Discover Weekly</a></li>
            </ul>
        </div>
        <div class="border-t border-gray-800 h-16 px-4  py-2 flex items-center group">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" 
                        stroke="currentColor" class="w-6 h-6 text-gray-600 group-hover:text-white">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 9v6m3-3H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                    </svg>
                    <a href="#" class="font-normal text-gray-500 ml-2 group-hover:text-white">
                        New Playlist
                    </a>
        </div>
      </div>
      <div class="content-spotify bg-gray-800-spotify flex flex-1 overflow-y-auto">
        Content Area. Lorem ipsum dolor sit, amet consectetur adipisicing elit.
        Ullam natus suscipit, tempore animi consequatur sunt aliquam non unde
        error. Eveniet, nemo perferendis quo optio unde esse ea sunt quidem
        soluta nam eaque fuga consectetur nisi repudiandae delectus deleniti aut
        voluptatem, nulla officiis dicta magni, eum fugit porro. Consectetur ea
        consequuntur quos, porro sunt ipsa ipsum eius, accusamus doloribus
        voluptatibus deserunt placeat eum nesciunt voluptates illum totam?
        Officiis nam suscipit obcaecati placeat! Sapiente, voluptatem? Repellat
        dolorem voluptatum nemo ea accusantium non? Incidunt tempore aut autem,
        tempora inventore asperiores blanditiis hic ipsam repellat consequuntur
        tenetur laborum adipisci quidem earum quaerat maxime officiis quasi
        dolorem distinctio molestiae qui expedita quis delectus neque. Sint
        eligendi quasi nihil voluptatem quidem fugiat quia doloremque rerum
        minima totam aliquam maiores repudiandae accusantium autem qui aliquid
        recusandae sed expedita voluptatibus quas itaque, voluptatum omnis?
        Itaque praesentium aperiam quibusdam corporis minus placeat, tempore nam
        quas. Veniam quas nemo, tenetur id nobis minima nam ipsum iure
        distinctio commodi cum eos, porro, incidunt pariatur culpa. Nisi in
        asperiores non nulla tenetur facilis. Sint magnam nihil quam aperiam
        molestias culpa illo! Corrupti quod explicabo est a eligendi fugiat
        corporis beatae quisquam? Nostrum velit tempore ipsam eaque numquam
        repudiandae voluptate voluptatum consectetur cumque. Enim laborum
        maiores labore distinctio obcaecati, omnis esse nesciunt, commodi et
        laboriosam magnam optio natus aperiam cumque! Autem consectetur ea
        officia necessitatibus quas, et error praesentium obcaecati consequuntur
        magni quo cumque numquam inventore. Excepturi dicta sed corrupti
        consectetur neque provident quam deleniti, nostrum earum ad velit
        consequuntur, laboriosam nesciunt unde impedit? Numquam, doloremque non.
        Dolores similique fugiat, possimus at fuga odio optio debitis aut
        suscipit, recusandae dolorum exercitationem, illum magnam commodi.
        Aperiam aut ipsa dolore a illum ullam ipsum exercitationem accusantium
        in ab tenetur hic voluptate perferendis dolorum, harum qui. Ducimus,
        minus ea voluptate doloremque ipsa sed deleniti doloribus modi quam
        magni ab aut iure laudantium dolorem voluptas explicabo tempora saepe
        unde adipisci a perspiciatis, alias dolor cupiditate harum? Dolores
        aperiam dolor nam, nostrum dolorem molestiae explicabo in natus quam
        quod vero quibusdam rerum reiciendis maxime adipisci et totam laudantium
        odit eaque, mollitia blanditiis impedit perspiciatis nobis ad! Atque
        temporibus ipsa vero cum recusandae nesciunt reiciendis sit, veniam
        obcaecati, aut blanditiis expedita ipsum neque nobis optio enim
        delectus. Eaque inventore iusto autem id fugiat maiores quos, saepe
        sapiente recusandae error numquam, corrupti est accusantium minima
        voluptas obcaecati explicabo, facere officiis sed consectetur impedit?
        Adipisci nostrum asperiores omnis reiciendis perferendis veritatis sint
        numquam fugiat et. Doloremque voluptatibus expedita deleniti blanditiis,
        doloribus dignissimos eius eveniet fugiat dolorem molestias. Nobis enim
        molestiae consectetur cumque, nulla, unde culpa aliquid cum aperiam
        tempora facere explicabo, pariatur ad saepe. Unde ipsa natus eius, autem
        perspiciatis labore maiores eum et doloremque! Ab repellat dolorum nemo
        itaque, excepturi optio est ut, distinctio illo quia velit culpa
        similique. Vitae saepe odit facilis dolor perspiciatis, dignissimos
        ipsam velit ipsa aliquid dolore nihil nostrum a corporis minima nobis
        cum, voluptas iste? Vero earum, soluta optio sunt labore nemo.
        Aspernatur vel accusantium deserunt numquam odio minima exercitationem
        porro ipsum dolorem modi veniam assumenda, libero voluptas harum, in,
        consequatur consectetur maxime commodi! Odio atque, mollitia fugit,
        expedita eveniet accusamus at hic voluptates eligendi consequuntur
        dolorum nulla voluptatem saepe iure laboriosam. Harum beatae, ea numquam
        id natus, modi quia consequuntur officia est tempore consectetur eius,
        non obcaecati velit? Iure at aliquid, voluptates labore fuga doloribus
        exercitationem maxime pariatur dolorem illum expedita, sed similique
        cupiditate molestias minima inventore quidem obcaecati nostrum dolores
        rem fugit modi sit et commodi! Blanditiis, quisquam nobis tempore
        inventore excepturi perspiciatis eligendi esse velit repellendus
        consectetur magnam fugit rem possimus temporibus, ratione vero a
        asperiores officia quis nesciunt nisi voluptate distinctio quibusdam
        incidunt? Fuga, obcaecati sint dolor quidem deserunt voluptas. Enim iure
        consequatur ex sed vero deleniti quis accusantium commodi voluptates
        soluta libero odio assumenda at placeat aperiam asperiores eius, esse
        voluptas culpa nisi nulla dolores totam? A explicabo quam, blanditiis
        optio quibusdam ipsum in doloribus nemo eos consequuntur nostrum et
        molestiae. Id sed, natus dolore omnis deleniti ex autem tenetur in
        necessitatibus eos mollitia commodi at repellendus assumenda architecto
        quaerat obcaecati sunt quia corrupti nam velit provident illum? Ut
        provident accusantium assumenda recusandae nostrum fuga ex facilis illo
        quam, soluta eos quas debitis hic consequuntur nihil temporibus quia
        excepturi, ratione, a esse iusto! Cupiditate doloribus ex aliquam
        voluptates accusamus quod iste magnam non in sed vitae laudantium maxime
        veniam, aut, nobis quo facere expedita! Nulla ut quam fuga nihil
        blanditiis dolorum eligendi, harum repellendus vitae magni id
        consequuntur nesciunt hic dolorem minima architecto nemo voluptates
        perspiciatis ipsum consectetur voluptatem voluptate iure beatae aperiam.
        Earum, perspiciatis quasi. Facilis officiis harum illo aliquid
        voluptatem eveniet inventore libero consectetur, maiores debitis impedit
        molestias, voluptatibus explicabo provident assumenda numquam quibusdam
        animi aut ad ex ab itaque. Eos, cumque, voluptatum quibusdam eum facere
        culpa laudantium aut repellendus sunt rerum minima inventore voluptates?
        Earum assumenda sed, odio suscipit quam quis expedita autem recusandae
        nulla, dignissimos aut rerum corporis dolor molestias ullam. Iusto
        molestias distinctio, optio culpa error blanditiis minima quia
        repellendus ipsa, facere perspiciatis doloremque eos accusantium autem,
        excepturi quod? Nesciunt iusto et nostrum voluptatem ad iure quibusdam
        inventore id autem commodi vel dolor voluptates at perspiciatis
        blanditiis praesentium, harum, dolore esse veniam soluta, quidem quas
        enim est. Maxime libero corporis enim. At ea cupiditate suscipit totam
        tenetur repudiandae veniam eligendi, autem maxime facere pariatur
        voluptatibus reiciendis possimus magni nesciunt nulla! Quibusdam qui hic
        itaque odio nostrum est cumque libero iste amet numquam dolores ipsam
        suscipit dolorem perspiciatis assumenda voluptatibus delectus, soluta
        quas minima pariatur. Ipsum mollitia obcaecati suscipit tempora
        reiciendis aut harum non perferendis voluptatem, eum pariatur dolor
        minima aliquid corrupti possimus? Modi illo odit quos facere debitis
        unde maiores sit eos assumenda quidem mollitia neque magnam soluta,
        ullam, aliquam dolor? Est, libero dignissimos corporis repellat ipsum
        doloribus officia cupiditate aperiam placeat maxime! Asperiores quidem
        earum culpa dignissimos quo! Rem inventore dolores, adipisci provident
        cupiditate dignissimos unde totam eum libero earum vitae, excepturi
        asperiores delectus commodi praesentium neque cumque illo optio harum?
        Cumque voluptates consequuntur hic, totam repellat fuga, mollitia
        ratione laborum quae similique odit et modi? Pariatur, molestiae
        incidunt blanditiis tempora ea animi hic, facilis expedita dicta
        deserunt nemo maiores quia voluptatum cum! Quis minus nobis velit id
        quaerat ut! Magnam doloribus cumque eos inventore non officiis
        accusantium eaque quisquam veritatis deserunt fugiat asperiores, maiores
        similique sapiente sequi reiciendis maxime ipsa. Quae soluta rem facere
        enim, iste quidem laboriosam voluptatem eveniet ducimus beatae officia
        rerum commodi magnam eum velit earum illo exercitationem tempore ratione
        maiores repellendus provident hic? Tenetur libero placeat itaque
        consequatur eligendi provident facere laudantium illo sit perferendis
        possimus, ad ipsum iste. Voluptas, ipsum. Voluptas autem dolores tempora
        soluta, dignissimos, temporibus enim quasi vero nemo incidunt obcaecati
        laudantium non doloremque a, asperiores esse? Omnis, id, deserunt quidem
        porro atque dignissimos blanditiis magni nisi hic magnam, obcaecati
        repudiandae? Vero explicabo animi fuga modi voluptate voluptates non
        nemo hic eum praesentium nam impedit maxime, enim totam quaerat labore
        laudantium? Deleniti itaque labore, eius quisquam atque molestiae
        mollitia ipsa recusandae facilis consectetur non numquam maxime,
        reprehenderit adipisci consequuntur ipsum voluptatem velit quis
        laboriosam placeat. Beatae rerum corporis ducimus delectus corrupti
        molestiae officiis aliquid nobis iusto facere deserunt obcaecati
        blanditiis nam, alias nihil eaque assumenda sunt similique ipsam tempora
        accusamus! Illum modi suscipit explicabo. Ab magnam odio reiciendis
        officia beatae explicabo, nobis tempora enim ut voluptas facilis esse ex
        quaerat impedit culpa corrupti iste magni iusto! Est totam unde eaque
        fuga pariatur, illum blanditiis porro aspernatur quos repellat magni
        facere debitis nam? Consectetur alias, voluptate quidem pariatur quos in
        eius dolorem quo itaque? Officiis nisi sint quis quasi, numquam
        doloremque temporibus voluptate molestiae dolorem aliquam iusto suscipit
        animi explicabo molestias quam quae cum? Nesciunt aspernatur dolore illo
        incidunt blanditiis a cumque minima error quisquam mollitia. Dolore
        facere, exercitationem magni nihil omnis, deleniti ullam enim reiciendis
        ad quas accusantium, asperiores adipisci? Nisi, corrupti in ipsa, quo
        nemo excepturi totam repellat at voluptatibus perferendis aut, a omnis
        officia tempora corporis aspernatur nulla deleniti ab eligendi.
        Similique officia, eveniet nam deserunt ad laborum distinctio, ullam
        corporis nobis sunt corrupti vitae minima ipsa placeat reiciendis. Ex,
        exercitationem esse ipsam facere, minus recusandae, minima obcaecati eos
        odit veritatis porro repellat labore quaerat impedit perspiciatis
        repellendus harum aliquam id tempora? Quisquam vero aspernatur dolor
        nobis ut necessitatibus quis laudantium temporibus commodi facere eius,
        molestiae nostrum, excepturi voluptatibus, iure nulla pariatur sunt
        veritatis reiciendis iusto esse. Praesentium laborum voluptates modi
        optio veritatis labore ipsam perspiciatis aspernatur itaque repellat.
        Maiores quidem voluptatem ipsa. Inventore voluptatum excepturi rem
        voluptates tenetur earum voluptatem aspernatur, consectetur enim,
        architecto in ut ducimus blanditiis natus iusto cumque atque! Mollitia
        fugit ex molestiae ipsam vitae expedita hic sunt possimus nam deserunt
        excepturi et non, reiciendis blanditiis velit, sed laboriosam dolor
        doloremque harum deleniti error quis. Provident animi odio id tempore
        ipsum blanditiis cum vel nemo, ea suscipit illum doloribus iste iusto
        voluptatibus placeat reprehenderit earum assumenda voluptates alias? Eum
        iste beatae dolor animi. Voluptatem similique vitae fugit velit
        repudiandae, itaque impedit tempore consequuntur corporis rerum magni
        facilis dicta necessitatibus eius eveniet dignissimos praesentium
        deserunt quae blanditiis amet repellendus exercitationem illum?
        Molestias odit aliquam eos quo officiis nulla a provident cupiditate
        fugiat! Possimus, distinctio ad molestiae ut molestias dolor. Ab
        cupiditate eos doloremque modi consequuntur sequi debitis itaque
        repellendus, atque at nesciunt numquam eveniet quae pariatur delectus
        quam magni facere qui aperiam autem. Obcaecati perferendis laudantium
        atque possimus quae quo sequi distinctio ipsa vitae? Maiores, ullam sunt
        a, doloribus ut, id architecto error deserunt exercitationem repellat
        dolorem ipsam repellendus deleniti illo praesentium ex. Expedita velit
        error qui ducimus obcaecati doloremque distinctio porro dolorem quae
        sunt, molestiae nemo illo labore dolor possimus! Adipisci incidunt at in
        voluptatem sequi! Consequatur sunt voluptatem ipsam tenetur quisquam
        nulla ipsum aliquid, non libero ullam debitis dignissimos animi repellat
        esse veritatis impedit alias officiis consequuntur. Quam, dignissimos.
        Minus, rerum. Voluptate, voluptas deserunt sint nulla modi eos.
        Reprehenderit dignissimos mollitia corrupti cupiditate omnis esse
        expedita illo quod obcaecati. At iure perspiciatis modi nobis commodi
        molestiae adipisci tempore aliquam suscipit assumenda in, recusandae
        ipsam aut, sunt quas id iusto quisquam ratione odit aperiam. Laudantium
        itaque vel a consequatur laborum quibusdam aliquid hic, repellendus iure
        eum ipsum cum saepe explicabo culpa dolore sit in odio inventore omnis
        aut expedita minus non quasi? Maxime tempora aspernatur quaerat
        cupiditate, ad molestiae obcaecati natus ipsa quas placeat corrupti
        ipsam nobis, tenetur quis itaque incidunt! Eos nobis laudantium deleniti
        sint nihil possimus enim culpa, labore modi molestias exercitationem
        quidem ab dicta accusantium, repudiandae architecto atque quisquam.
        Aliquam voluptatibus, nobis autem ratione sed corporis natus hic
        molestiae. Ipsum, harum corporis accusantium iure tenetur modi minima
        dolor similique ab pariatur accusamus est repudiandae dignissimos
        deleniti! Saepe maiores iste iusto veniam nihil officiis magni molestiae
        obcaecati. Nulla tempora facere earum iste? Architecto corrupti et
        perferendis magni voluptates repudiandae deleniti, molestias repellat,
        exercitationem unde, quia nam! Beatae earum, blanditiis rerum nobis
        quasi facilis tempora distinctio adipisci corporis suscipit ullam quae
        non! Asperiores molestiae iusto doloremque aperiam in provident ab
        dolorem. Esse blanditiis suscipit quam ea aut, voluptate aspernatur
        temporibus natus vitae laudantium! Enim et culpa molestiae voluptatem
        distinctio nobis optio reprehenderit assumenda. Tempora totam qui
        nesciunt nisi vel numquam ullam, veniam amet nostrum, molestiae,
        exercitationem assumenda eveniet. Ipsam praesentium fuga laudantium
        assumenda dicta sed provident quas sunt cupiditate temporibus repellat
        necessitatibus impedit animi nobis voluptatum laborum, officia vitae,
        minus aspernatur! Quam a, tenetur vitae voluptates dolores iusto
        aspernatur quo pariatur labore nobis quae quasi ut ea velit doloremque
        unde possimus molestiae? Atque reiciendis amet obcaecati quas dicta,
        repellat assumenda facilis ipsum nisi quidem numquam? Soluta veritatis
        ipsam suscipit pariatur cum expedita est repellat maiores error adipisci
        modi atque accusantium doloribus, rerum et in beatae libero sed! Cumque
        nihil ab non mollitia eveniet rem possimus quia tempore necessitatibus,
        nostrum magnam aspernatur id eum impedit dicta ipsa dolorem autem
        suscipit et, nemo consequuntur deleniti ratione iusto maiores! Maxime,
        accusantium neque. Nulla in impedit nisi neque cumque! Dolorem, animi
        ad. Quidem accusantium neque rerum velit, nisi consectetur omnis impedit
        necessitatibus vero delectus iure illum, inventore aliquam recusandae
        optio ipsum esse corrupti quisquam quas quod saepe odio ducimus debitis
        commodi! Dolores, ipsa.
      </div>
    </div>
    <div class="bg-gray-700 flex-none flex h-22 items-center px-5 border-0 justify-between">
            <!-- left item //-->
            <div class="flex items-center border-0">
                    <a href="#"><img :src="image2" alt="album cover" class="w-14 h-14"></a>
                    <div class="ml-3">
                            <div><a href="#" class="hover:text-white">Name of Song</a></div>
                            <div class="text-xs text-gray-500 hover:underline hover:text-white">Artist Name</div>
                    </div>
            </div>
            <!-- end of left item //-->
            <!-- center item //-->
            <div class="player-controls flex flex-col border-0 justify-center">
                    <div class="flex justify-center">
                            <button class="border-0 px-2">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M6 13.5V3.75m0 9.75a1.5 1.5 0 010 3m0-3a1.5 1.5 0 000 3m0 3.75V16.5m12-3V3.75m0 9.75a1.5 1.5 0 010 3m0-3a1.5 1.5 0 000 3m0 3.75V16.5m-6-9V3.75m0 3.75a1.5 1.5 0 010 3m0-3a1.5 1.5 0 000 3m0 9.75V10.5" />
                                    </svg>


                            </button>
                            <button class="border-0 px-2">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
                                </svg>
                            </button>

                            <button class="border-0 px-2">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 5.653c0-.856.917-1.398 1.667-.986l11.54 6.348a1.125 1.125 0 010 1.971l-11.54 6.347a1.125 1.125 0 01-1.667-.985V5.653z" />
                                    </svg>
                            </button>
                            <button class="border-0 px-2">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
                                    </svg>

                            </button>
                            <button class="border-0 px-2">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99" />
                                    </svg>


                            </button>
                    </div>
                    <div class="max-w-full mt-3 flex items-center justify-center">
                            <div class="text-xs text-gray-500">1:20</div>
                            <div class="bg-gray-500 rounded w-full xl:w-200 h-1 ml-3"></div>
                            <div class="ml-3 text-xs text-gray-500">3:21</div>
                    </div>
            </div>
            <!-- end of center item //-->
            <!-- right item //-->
            <div class="flex item-center">
                    <button class="px-2">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 7.5V6.108c0-1.135.845-2.098 1.976-2.192.373-.03.748-.057 1.123-.08M15.75 18H18a2.25 2.25 0 002.25-2.25V6.108c0-1.135-.845-2.098-1.976-2.192a48.424 48.424 0 00-1.123-.08M15.75 18.75v-1.875a3.375 3.375 0 00-3.375-3.375h-1.5a1.125 1.125 0 01-1.125-1.125v-1.5A3.375 3.375 0 006.375 7.5H5.25m11.9-3.664A2.251 2.251 0 0015 2.25h-1.5a2.251 2.251 0 00-2.15 1.586m5.8 0c.065.21.1.433.1.664v.75h-6V4.5c0-.231.035-.454.1-.664M6.75 7.5H4.875c-.621 0-1.125.504-1.125 1.125v12c0 .621.504 1.125 1.125 1.125h9.75c.621 0 1.125-.504 1.125-1.125V16.5a9 9 0 00-9-9z" />
                                </svg>

                    </button>
                    <button>

                    </button>
                    <button>
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M19.114 5.636a9 9 0 010 12.728M16.463 8.288a5.25 5.25 0 010 7.424M6.75 8.25l4.72-4.72a.75.75 0 011.28.53v15.88a.75.75 0 01-1.28.53l-4.72-4.72H4.51c-.88 0-1.704-.507-1.938-1.354A9.01 9.01 0 012.25 12c0-.83.112-1.633.322-2.396C2.806 8.756 3.63 8.25 4.51 8.25H6.75z" />
                            </svg>


                    </button>
                    <button class="bg-gray-500 rounded-lg w-20 h-1 ml-3 mt-2"></button>
                    <button class="px-2">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9.594 3.94c.09-.542.56-.94 1.11-.94h2.593c.55 0 1.02.398 1.11.94l.213 1.281c.063.374.313.686.645.87.074.04.147.083.22.127.324.196.72.257 1.075.124l1.217-.456a1.125 1.125 0 011.37.49l1.296 2.247a1.125 1.125 0 01-.26 1.431l-1.003.827c-.293.24-.438.613-.431.992a6.759 6.759 0 010 .255c-.007.378.138.75.43.99l1.005.828c.424.35.534.954.26 1.43l-1.298 2.247a1.125 1.125 0 01-1.369.491l-1.217-.456c-.355-.133-.75-.072-1.076.124a6.57 6.57 0 01-.22.128c-.331.183-.581.495-.644.869l-.213 1.28c-.09.543-.56.941-1.11.941h-2.594c-.55 0-1.02-.398-1.11-.94l-.213-1.281c-.062-.374-.312-.686-.644-.87a6.52 6.52 0 01-.22-.127c-.325-.196-.72-.257-1.076-.124l-1.217.456a1.125 1.125 0 01-1.369-.49l-1.297-2.247a1.125 1.125 0 01.26-1.431l1.004-.827c.292-.24.437-.613.43-.992a6.932 6.932 0 010-.255c.007-.378-.138-.75-.43-.99l-1.004-.828a1.125 1.125 0 01-.26-1.43l1.297-2.247a1.125 1.125 0 011.37-.491l1.216.456c.356.133.751.072 1.076-.124.072-.044.146-.087.22-.128.332-.183.582-.495.644-.869l.214-1.281z" />
                            <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                            </svg>

                    </button>
                    
            </div>

            <!-- end of right item //-->

    </div>
  </div>
</template>


<script>
    import image1 from './covers/c1.jpg'
    import image2 from './covers/c2.jpg'

    export default {
        data: function(){
            return {
                image1: image1,
                image2: image2
            }
        }
    }
</script>





<style>
    .sidebar-spotify::-webkit-scrollbar{
        width: 8px;
        background-color: #121212;
    }

    .sidebar-spotify::-webkit-scrollbar-thumb{
        border-radius: 8px;
        background-color: #535353;
    }

    .content-spotify::-webkit-scrollbar{
        width: 8px;
        background-color: #181818;
    }

    .content-spotify::-webkit-scrollbar-thumb{
        border-radius: 8px;
        background-color: #535353;
    }
</style>
