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
      <div class="content-spotify bg-gray-800-spotify flex flex-col flex-1 overflow-y-auto">
                <div class="topbar flex justify-between px-4 py-2">
                        <div class="flex items-center">
                            <button>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
                                </svg>

                            </button>
                            <button class="ml-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
                                </svg>

                            </button>
                            <div class="ml-4 relative">
                                <input type="text" placeholder="Search" class="bg-white text-gray-800 
                                placeholder-gray-800 rounded-full px-3 pl-8 py-1" />
                                    <div class="absolute top-0">
                                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 pt-1 pl-2">
                                            <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                                            </svg>
                                    </div>

                            </div>
                        </div>
                        <div class="flex items-center">
                                <button>
                                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                            <path stroke-linecap="round" stroke-linejoin="round" d="M17.982 18.725A7.488 7.488 0 0012 15.75a7.488 7.488 0 00-5.982 2.975m11.963 0a9 9 0 10-11.963 0m11.963 0A8.966 8.966 0 0112 21a8.966 8.966 0 01-5.982-2.275M15 9.75a3 3 0 11-6 0 3 3 0 016 0z" />
                                            </svg>
                                </button>
                                <a href="#" class="ml-2 hover:underline hover:text-white">ebubeokoh</a>
                                <button class="ml-4">
                                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5" />
                                        </svg>

                                </button>
                                

                        </div>

                </div>
                <div class="content-spotify overflow-y-auto">Content. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quia suscipit quibusdam at expedita, repellendus voluptas provident totam ad tempora nobis. Minus fugit ut, perferendis veniam eligendi hic exercitationem id harum nostrum suscipit quam voluptatibus placeat expedita quod totam quas tempore est necessitatibus deserunt modi unde mollitia iusto minima dolore! Sunt officiis atque, eaque odit unde obcaecati ipsam enim sint numquam quod nihil dolore et dignissimos ad iusto temporibus laboriosam neque iste nulla. Facere iusto minus dolore laudantium molestiae, facilis incidunt perferendis voluptatibus error accusantium dolorum similique reiciendis, distinctio atque voluptas excepturi repellendus. Dignissimos beatae quidem temporibus dolore magni quas expedita iusto blanditiis numquam commodi, pariatur deserunt. Impedit sequi fugit possimus modi a, cum, enim magnam sint eius perferendis blanditiis! Quam impedit ad deserunt! Corporis excepturi voluptates delectus expedita ut modi deserunt? Optio eveniet natus numquam, placeat asperiores labore magnam ipsa libero fugiat cumque. Neque ducimus magnam provident maiores expedita eligendi nemo error, vero odio ut ipsa. Earum rerum modi iure ab molestias, nesciunt in blanditiis velit eos amet delectus. Cum porro animi dignissimos quisquam quidem sint dolor accusamus quibusdam non tempore aliquam repudiandae provident alias quae, asperiores delectus doloribus. Repudiandae earum molestias nobis aliquid distinctio, necessitatibus alias harum dignissimos temporibus dolore magnam, sed vel quod. Possimus, dolore. Labore dolorem inventore, veniam voluptatem nam blanditiis. Libero porro, temporibus aut corporis nihil sed possimus nulla, provident culpa, sequi totam quaerat repudiandae soluta impedit reprehenderit enim laboriosam aspernatur! Assumenda dicta odit ea voluptatibus? Illum non voluptatem cupiditate repellendus sed beatae consequatur quae vitae nisi odit aperiam rem ipsum repellat consequuntur, natus ex earum. Nesciunt cum quo aperiam accusantium quibusdam mollitia alias dolores ratione ab eveniet, perspiciatis repellat, exercitationem aliquid earum incidunt debitis hic iure veritatis facere cupiditate enim autem unde deleniti? Cumque sed sunt animi fugiat nihil, eius quo ratione quos enim iure qui rem ipsa repudiandae. Recusandae repudiandae tenetur et aperiam, est pariatur itaque nam nesciunt, quidem temporibus eaque amet placeat saepe quas deserunt quos provident eveniet laborum, explicabo quis vitae. Fuga aliquid amet illo facilis ratione harum temporibus sequi minus magnam, sint in magni provident, adipisci iusto assumenda debitis vero dicta perferendis corporis necessitatibus, nam et. Ipsa esse, ea a, ratione est ducimus temporibus atque magnam reiciendis accusamus officiis et suscipit odit id doloribus corporis dolores accusantium minima eum animi debitis, illo voluptate fugiat! Qui voluptatum labore impedit provident ratione et laudantium debitis. Repellendus quis tempore, ut impedit eligendi nisi aliquid soluta nulla voluptatem eos, nihil earum veritatis, quidem maxime vitae excepturi ab odio quod officia? Nisi dolore voluptatem quasi adipisci praesentium, facilis tempora? Et cupiditate cumque optio neque harum odio sapiente! Fuga ea sit illum, earum quas eveniet dolor nemo corrupti fugiat porro aliquam provident, quam iste aspernatur aut asperiores nulla, necessitatibus in doloremque architecto ut placeat sed quod facilis. Sint sed totam minus non quisquam eveniet accusamus reiciendis rerum, in qui est? Iste alias, deserunt aut quae odit magnam iusto itaque exercitationem illum natus id soluta molestiae obcaecati maiores in, beatae fuga iure ullam adipisci sequi tempora. Ipsum est aut iusto! Facilis animi recusandae magni, ducimus, quas pariatur veniam enim, eius inventore ab ipsa laborum. Voluptatibus, harum facere. Saepe cumque blanditiis illum nisi nobis aperiam minima beatae modi cum necessitatibus earum, veritatis dolorem qui veniam dolores doloribus odio nemo delectus dignissimos distinctio iure temporibus in quasi! Laboriosam ipsam esse magni vero corporis, beatae animi delectus aliquam alias? Voluptate dolores est dignissimos asperiores quae natus nesciunt earum aliquid illo at veniam tempore ut molestias debitis aliquam inventore, voluptas nostrum quas facere vel, molestiae tenetur? Quas, ex deserunt soluta error quos aperiam accusamus dolorum omnis aspernatur veritatis distinctio enim nihil excepturi ab iste earum debitis, provident minima eius culpa delectus mollitia tempore. Inventore ad obcaecati velit harum hic, labore, nulla ab maiores accusamus esse ut. Assumenda tempore explicabo nulla rerum sapiente aspernatur aperiam asperiores soluta quaerat inventore perspiciatis, illo unde commodi nihil atque minima delectus fugiat ipsum ipsam earum sunt tenetur. Earum odit velit natus ad eius dolorem quo hic numquam voluptatum vitae aperiam maiores ratione beatae quam eum ducimus, dignissimos iure saepe, corporis rem ex. Porro asperiores fugit ipsa autem totam laborum voluptate laboriosam, dignissimos nisi, rem amet deserunt, minima accusamus odit! Rerum corporis debitis unde libero ipsam quas aperiam saepe vel dolores perferendis fugit corrupti veniam ab, illum illo molestias. Nobis blanditiis cupiditate praesentium esse animi. Voluptate doloremque temporibus tempora nemo, dolor ad. Repudiandae beatae debitis unde quam fugit, ducimus nulla culpa hic provident voluptate quaerat ex perferendis magnam maxime maiores. Perferendis corporis id asperiores excepturi odit optio! Voluptatem totam nulla magnam ea, est quia incidunt cupiditate ipsa, doloremque ut obcaecati! Asperiores, in modi quas repellat quibusdam placeat fugit ipsum magni esse porro maiores rerum architecto veritatis omnis deserunt tenetur obcaecati saepe, recusandae incidunt ducimus, quo soluta expedita accusamus? Fugit quod autem doloribus neque? Doloremque hic esse adipisci exercitationem quia laborum corrupti excepturi quisquam officia nobis molestiae voluptatem blanditiis aperiam repellendus autem ad, accusamus est impedit ratione illo explicabo alias sapiente. Temporibus sed quae recusandae ea architecto esse quas blanditiis itaque a expedita dolorum earum, dicta nihil voluptas natus saepe non iure numquam repellat alias mollitia illo? Modi alias perferendis quae tempore facere maiores? Itaque deleniti aut provident, mollitia quidem veritatis aperiam a illum qui iusto totam et, saepe eos facilis accusamus eveniet consectetur! Repellat expedita saepe corporis odio optio iure quisquam id, repudiandae cumque eius quos quae modi dolorum ad error voluptatum nemo laudantium quia! Ratione ab, ipsam accusantium iusto excepturi, voluptatum atque laborum ipsum nihil, earum laboriosam corporis totam eligendi sapiente quisquam illo maxime? Voluptatibus deleniti voluptates repudiandae omnis enim recusandae amet temporibus sapiente quis doloremque debitis, sed deserunt molestiae nisi quibusdam alias facilis autem ratione placeat fuga excepturi sit nihil. Facere labore voluptas ullam et magnam explicabo itaque commodi aliquid voluptatum. Soluta praesentium illo exercitationem quos dignissimos deserunt facere eius quae blanditiis, expedita earum adipisci aliquid et? Fuga perspiciatis dolore maiores quasi illum, deleniti libero unde quos hic, delectus at. Tenetur nisi optio aut, corrupti cupiditate nam laborum debitis nostrum nihil quisquam voluptatem dignissimos consequatur ut eveniet ipsum dolorem! Non voluptates odit ipsam aspernatur tempore hic, assumenda repellat explicabo illum excepturi minus accusantium laborum saepe beatae harum in enim maiores facilis quidem perferendis ea? Nisi error, natus eligendi at voluptates doloribus quibusdam quam quis distinctio corrupti laudantium est dolore laborum porro dolorem ratione consectetur nihil numquam architecto, cum dolores itaque neque, aspernatur magni? Nesciunt delectus fugiat numquam porro alias? Soluta, dignissimos deserunt? Harum hic magni libero, error ut reiciendis sit dolorum ipsa molestias, ex doloremque dignissimos laudantium temporibus illo, quam id nihil! Temporibus, cupiditate exercitationem. Dicta dolore iusto autem. Quam nesciunt sint doloremque iure qui aspernatur, laborum incidunt odio, facilis quod voluptatem illo, eligendi perspiciatis minima porro beatae quasi harum doloribus accusamus magni. In maiores, cumque ipsam, magnam facilis omnis, animi eius ratione deleniti neque quo. Voluptatibus ipsum ipsa possimus exercitationem cum ad quibusdam consectetur quis ducimus perferendis facere obcaecati eius modi eaque fugiat perspiciatis, placeat expedita blanditiis at numquam. Sunt voluptates error atque aliquid, eos in expedita corporis quas, ut est magnam saepe nemo magni quaerat esse deserunt repellendus. Veritatis nostrum veniam voluptatum perspiciatis doloremque corporis exercitationem illum explicabo quam amet velit numquam nemo quo, distinctio nam tenetur vero. Perspiciatis ducimus id, nulla quas iure aspernatur provident laudantium rerum quod placeat ratione recusandae saepe, officiis voluptas numquam quisquam ipsum! Nemo impedit omnis ut dolor, magni sapiente. Deserunt aliquid in explicabo quia, perferendis quisquam, sunt officiis natus fugit neque, soluta ut ab numquam? Fugit at debitis dolorum animi facere? Necessitatibus, laboriosam nihil nostrum repellat esse ducimus alias fugit sapiente atque mollitia commodi, aliquam consequuntur ullam fuga illum tempore temporibus. Rerum doloremque quaerat hic nostrum labore quod ipsa enim quas numquam. Corrupti odit officia repellat nostrum illum incidunt, a dignissimos iure optio at asperiores esse ipsam hic eaque libero voluptatibus expedita quam necessitatibus nobis ex harum? Cupiditate aperiam mollitia non, molestias quas enim. Cupiditate a hic maiores deleniti aut, animi sunt nostrum ut praesentium reprehenderit alias quibusdam, ex dignissimos ea, facere eos nemo dolorem modi perspiciatis earum! Esse consequuntur cupiditate expedita consectetur architecto odio qui est debitis eveniet. Error quis dolor ducimus mollitia repellendus enim earum exercitationem vitae, perferendis autem assumenda nostrum consectetur, soluta quam? Magnam officia eveniet ipsam exercitationem quam, accusantium id, nemo deserunt accusamus perferendis dolor obcaecati, minus quasi aliquid repellat odio facere. Magni rem, cum provident autem, unde repudiandae, nulla exercitationem in eius molestiae praesentium quas saepe eveniet! Totam accusantium, praesentium id consectetur corporis dolores temporibus! Deleniti corrupti perferendis, aliquam quasi voluptatibus itaque similique odio eum aperiam, eveniet ducimus accusantium temporibus consequuntur eos suscipit sint. Repellendus facere asperiores blanditiis facilis ullam eos numquam quos corrupti. Dolores aut distinctio alias omnis? Laboriosam, maxime illo laborum recusandae eaque sequi animi ducimus itaque nam incidunt mollitia et accusantium nobis delectus culpa debitis, asperiores saepe. Quidem est reprehenderit maiores! Numquam, commodi temporibus suscipit, similique dolor dolores sint soluta molestias eveniet adipisci quam sed dolorem recusandae libero provident officiis officia ad illo aspernatur ducimus possimus? Cupiditate molestiae rerum beatae nemo officiis, laboriosam voluptatibus iusto temporibus vel at asperiores! Saepe, ipsa dolorem veniam reiciendis libero dolor labore, quaerat in minus, fugit aut. Eligendi dolorum possimus minima officia maiores, voluptatem, ullam odio ea iste eaque explicabo minus vitae voluptatum veritatis quo, asperiores aut pariatur quidem alias quod! Atque magni ipsa, sequi dolor, eos, numquam laborum amet iusto debitis blanditiis illo dignissimos sapiente cumque consectetur iure tempora neque et nisi enim provident incidunt officia corrupti totam sit. Porro fugit similique quasi rerum maxime corrupti nesciunt, eaque molestiae, cum soluta pariatur hic sed consequatur aliquid totam suscipit dolorem reprehenderit itaque eius quos veniam? Recusandae placeat fugit qui inventore nobis tempora doloribus. Explicabo saepe tenetur corporis voluptatibus veritatis voluptatum, quaerat a, facere nostrum quos distinctio possimus quasi esse sit voluptas deserunt incidunt quibusdam asperiores architecto. At iure, molestias maiores autem quas neque error assumenda ratione in, omnis placeat. Repellat explicabo velit reprehenderit molestiae sapiente fuga obcaecati voluptas tenetur, ut nesciunt, consequatur at cupiditate odit dolore accusantium modi quidem ipsa architecto nam similique veniam ab? Distinctio pariatur tempore a, sequi aperiam facilis corrupti fugiat at! Laborum labore pariatur facilis, itaque maiores nemo similique eligendi explicabo eius error ducimus perspiciatis placeat quod quam consectetur fugit sit. Totam laborum maiores aspernatur quidem quos vel sint est, adipisci quas laboriosam earum placeat explicabo nesciunt itaque magni hic fuga dolor? Voluptatum eum animi odio quasi amet nihil et alias, obcaecati possimus similique, nulla iure. Inventore dicta voluptates blanditiis enim commodi? Soluta, impedit provident ab et minus quidem at quia corporis vero dolor incidunt obcaecati. Dolorum commodi accusantium tempore hic aliquam quis, distinctio mollitia ab, illo fuga error eum aliquid ratione rem voluptas inventore amet autem deleniti fugit voluptates est consequatur neque placeat blanditiis? Perferendis nam nulla ex beatae nobis. Eligendi impedit veniam at ut voluptas, sit quod unde deleniti ipsum qui aut earum aperiam vel alias velit amet non, deserunt sunt pariatur cum quia soluta quibusdam accusamus? Deleniti cumque voluptatem cum quidem mollitia nostrum ipsum corrupti saepe ipsa fugiat, architecto incidunt est repellat, exercitationem ducimus quaerat vero voluptates harum! Harum ducimus, laudantium itaque ipsum, blanditiis rerum porro saepe qui illo animi consectetur quaerat at omnis tenetur veniam in sequi! Voluptates minus iste repellendus sed expedita, vero nobis sint reiciendis non fugiat laudantium, accusantium, nihil enim. Maxime voluptates inventore architecto provident esse nam magni. Recusandae voluptates quis omnis quam. Distinctio sapiente molestias eaque ea saepe sit unde, quae vero itaque quod enim ullam sunt, quasi est quaerat nobis officia, eveniet cum aut aperiam error a magni? Quos doloribus ex eligendi aut esse unde, sit ipsa error excepturi? Adipisci unde repellat, corporis pariatur provident quam repellendus. Et eligendi amet dignissimos ipsa vero autem praesentium nesciunt fuga quo accusamus voluptatem delectus, laboriosam tempora? Quod adipisci quas voluptatibus perspiciatis mollitia? Velit modi fugit, odio laboriosam sunt ab itaque dolorem et dolore voluptates hic nulla voluptate amet reprehenderit repellendus? Sequi aliquam officia blanditiis soluta, modi maxime saepe in, quidem placeat nemo cupiditate esse! Soluta alias molestiae, inventore quis dolorum ducimus. Facere saepe modi dignissimos dolores architecto aliquam, consequuntur facilis, quibusdam hic omnis fuga quisquam!</div>
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
