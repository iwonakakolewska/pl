<!DOCTYPE HTML>
<html>
    <head>
        <meta charset="utf-8"/>
        <link href="https://fonts.googleapis.com/css?family=Dosis" rel="stylesheet">
        <title>Rozwoj dzieci</title>
        <style>
            * {
                margin: 0;
                padding: 0;
            }
            body {
                font-family: 'Dosis', sans-serif;
                background:white;
            }
            #menugorne {
                width:100%;
                background-color: #e84040;
                height: 40px;
                text-align: center;
            }
            #menu li {
                position: relative;
                float: right;
                list-style-type: none;
                width:25%;
                background: #e84040;
                text-align: center;
                padding-top: 10px;
                padding-bottom: 10px;
                font-size: 15;
                color: white;
            }
            
            #menu li:hover {
                background-color: #ef7373;
            }
            #menu {
                width:80%%;
                margin-left: auto;
                margin-right: auto;
            }
            h1 {
                text-align: center;
                color: black;
                margin-bottom: 5px;
                font-size: 50px;
                padding-top: 50px;
                
            }
            #omnie {
                width:80%;
                height: auto;
                background-color:white;
                margin-bottom: 50 ;
                margin-left: auto;
                margin-right: auto;
                
            }
          
            #iwona {
                margin-left: 3%;
                margin-top: 3%;
            }
            
            .duzytekst {
                margin-bottom: 20px;
                font-size: 19px;
            }
            h3 {
                margin-top: 30px;
                margin-left: 50px;
                font-size:18px;
                
            }
            h4 {
                margin-left: 50px;
                font-size:18px;
                
            }
            #literatura {
                margin-bottom: 50px;
                margin-left: auto;
                margin-right: auto;
                width:80%;
                height: auto;
            }
            #zalaczniki {
                margin-bottom: 50px;
                margin-left: auto;
                margin-right: auto;
                width:80%;
                height: auto;
            }
            #tabelawyksztalcenie {
                margin-top:50px;
                height: auto;
                width: auto;
                min-width: 80%;
            }
            label {
                display:none;
            }
            #toggle {
                display: none;
            }
            @media only screen and (max-width:1000px) {
                label {
                    display: block;
                    cursor: pointer;
                    color:white;
                    font-size: 20px;
                    padding-top: 8px;
                }
                #menu li{
                    width: 100%;
                    text-align:center;
                    display:none;
                }
                #toggle:checked + #menu li {
                   display: block; 
                }
                #menugorne {
                    padding-top: 15px;
                    padding-bottom: 15px;
                }
     
            }
            .sticky {
                width: 100%;
                position: fixed;
                left: 0;
                top: 0;
                z-index: 100;
            }
            .literaturatext {
                width: 80%;
                background: blue;
            }
            .poletext {
                width: 80%;
                height: auto;
                font-size: 12;
                margin: 30px auto 0 auto;
            }
            @media only screen and (max-width:1100px) {
                #iwona {
                    width: 70%;
                    height: 20%;
                    text-align: center;
                    margin-left: 15%;
                    margin-right: 15%;
                }
            }
            #koncowka {
                width:100%;
                background-color:#ef7373;
                
            }
            .koncoweczka {
                text-align: center;
                padding-top: 15px;
                padding-bottom: 15px;
                color: white;
            }
            #duzytekst {
                width: 68%;
                height: auto;
                float: right;
                margin-top: 3%;
            }
            .link {
                text-decoration: none;
                color:white;
            }
            @media only screen and (max-width:1290px) {
                #duzytekst {
                    width: 100%;
                    height: auto;
                }
                #iwona {
                    width: 70%;
                    height: 20%;
                    margin-left: 15%;
                    margin-right:15%;
                }
            }
            @media only screen and (min-width:1500px) {
                #duzytekst {
                    width: 72%;
                }
            }
            @media only screen and (min-width:1800px) {
                #duzytekst {
                    width: 80%;
                }
                #iwona {
                    width: 230px;
                    height: 300px;
                }
            }
        </style>
        
        
    </head>
    <body>
        <div id="menugorne">
            <label  id="label" for="toggle">&#9776;</label>
            <input type="checkbox" id="toggle"/>
            <ul id="menu">
                <a class="tekst1" href="#zalaczniki"><li >Załączniki</li></a>
                <a class="tekst1" href="kacik-rodzicow.html"><li >Kącik rodzica</li></a>
                <a class="tekst1" href="#literatura"><li  >Literatura</li></a>
                <a class="tekst1" href="#omnie"><li >O mnie</li></a>
            </ul>
        </div>
        
        <div id="omnie">
        <h1>O mnie</h1>
        <hr weight="100%" color="#e84040">
        <img id="iwona"src="iwona.jpg.PNG" width="300" height="400px"/>
            <div id="duzytekst">
                <div id="zzz">
       <h4 class="duzytekst" >Nazywam się Iwona Kąkolewska. Pracuję od 25 lat z dziećmi w wieku przedzkolnym. Jestem nauczycielem mianowanym: wychowania fizycznego, wychowania przedszkolnego, fizjoterapetuą, oligofrenopedagogiem, a także terapeutą ręki. Dodatkowo zawodowo interesuję się psychologią oraz medycyną. Prywatnie pasjonują mnie zagadnienia dotyczące nauki, historii oraz przyrody. Bardzo lubię pomagać innym ludziom i w pełni realizuję się w pracy terapeuty. Moja ciekawość świata, gotowość do podejemowania nowych wyzwań, samodoskonalenia oraz umiejętność dostosowania do zmieniających się warunków sprawiają, że praca jest dla mnie pasją, nie tylko źródłem utrzymania. Solidne przygotowanie teoretyczne i praktyczne, pozwala mi na właściwe podejście do dziecka.</h4>
                 </div>
            <div id="xxx">
        <h4   class="duzytekst">Na mojej stronie internetowej zachęcam rodziców do pracy z dziećmi. Będę regularnie zamieszczała ćwiczenia. Zorganizuję to w taki sposób, żeby były to zadania dostosowane do wszystkich dzieci oraz do dzieci z różnymi potrzebami (porażenie mózgowe, zespół Downa, nadpobudliwość psychoruchowa, zaburzenia motoryki ręki, dzieci z autyzmem, hipochondroplazją, itd.). Wykorzystam w tym celu od lat gromadzoną w mojej bibliotece literturę.</h4>
             </div>
            </div> 
            
            <div id="tabelawyksztalcenie">
            <h3>Moje kwalifikacje oraz kursy i szkolenia:</h3>
            <h4>-Medyczne Studium Zawodowe w Ostrowie Wielkopolskim - technik fizjoterapii,</h4>
            <h4>-Studia magisterskie - Akademia Wychowania Fizycznego w Poznaniu, Wydział Wychowanie Fizyczne - kierunek nauczycielski,</h4>
            <h4>-Studia magisterskie - Akademia Wychowania Fizycznego w Poznaniu - kierunek rehabilitacji ruchowej,</h4>
            <h4>-Ośrodek Metodyczny w Poznaniu - Warsztaty Metodyczne z Zakresu Wychowania Przedszkolnego w wymiarze 90 godzin,</h4>
            <h4>-Uniwersytet Adama Mickiewicza w Poznaniu - Studia Podyplomowe w zakresie Wychowania Przedszkolnego,</h4>
            <h4>-Wojewódzki Ośrodek Metodyczny w Poznaniu - Kurs Kwalifikacyjny z zakresu Oligofrenopedagogiki w wymiarze 260 godzin,</h4>
            <h4>-Pedagogika zabawy - zarys metod aktywizujących,</h4>
            <h4>-Symultaniczno-sekwencyjna nauka czytania - warsztaty organizowane przez Centrum Metody Krakowskiej,</h4>
            <h4>-Konferencja pt. ,,Edukacja dzieci z niepełnosprawnością'',</h4>
            <h4>-Szkolenie pt. ,,Praca Zespołowa Nauczycieli Przedszkola'',</h4>
            <h4>-Terapia ręki I i II stopień,</h4>
            <h4>-Szkolenie ,,Trudności w zakresie przywiązania, a funkcjonowanie dzieci w przedszkolu'',</h4>
            <h4>-Szkolenie ,,Dziecko autystyczne w edukacji włączającej'',</h4>
            <h4>-Wojewódzkie Seminarium dla Nauczycieli - Intelignecja ręki w edukacji szkolnej,</h4>
            </div>
        </div>
  
        <div id="literatura">
        <h1>Literatura</h1>
        <hr width="100%" color="#e84040">
        <h4 class="poletext">W tej zakładce będę proponowała książki i pomoce, które są godne polecenia. Powinny ułatwić rodzicom pracę z dziećmi. Postaram się skrótowo nakreślić do kogo są adresowane i jakie kompetencje pomogą rozwinąć. Warto pracować z dziećmi dodatkowo w domu i rozwijać ich zdolności, ponieważ mózg małego dziecka w nieograniczony sposób przyjmuje pobudzenia. Im więcej bodźców dziecko otrzymuje, tym więcej komórek mózgowych aktywizuje się na całe życie. Wiadomo, że liczne ćwiczenia i powtórzenia utrwalające są warunkiem wszelkiego uczenia się.  Stąd też moje propozycje związane z gromadzeniem różnorodnych pomocy i literatury fachowej.
        </h4>
        <h4 class="poletext">Dla ułatwienia pracy z dzieckiem, chciałabym zaproponować rodzicom poradnik dla pedagogów, logopedów i rodziców dzieci z trudnościami w porozumiewaniem się pt. ,,Od obrazka do słowa’’ - Hanna Rodak, Danuta Nawrocka, wydawnictwa Szkolne i Pedagogiczne. Są to pomoce przygotowane w formie pozwalającej na prowadzenie wielu różnych gier indywidualnych oraz zabaw. Opracowanie jest odzwierciedleniem etapów postępowania terapeutycznego w procesie rozwijania mowy. Zawiera również przewodnik, w którym zostały określone pedagogiczne zasady postępowania z dzieckiem w wieku przedszkolnym. Materiał językowy przedstawiony jest w formie luźnych arkuszy z obrazkami, które są podpisane z tyłu. Wielkość etykiet jest odpowiednia dla dzieci w wieku 4-5 lat. Pozycja wspomaga również rozwój kompetencji poznawczych, ponieważ jest podzielona na odpowiednie bloki tematyczne.
        </h4>
        <h4 class="poletext">
            Chciałabym Państwu zaproponować bardzo ciekawą pozycję, która przyda się wszystkim osobom, pracującym z dziećmi wymagającymi dodatkowego wsparcia. Książka nosi tytuł ,,Wczesna diagnoza i terapia zaburzeń autystycznych. Metoda Krakowska’’. Jej autorką jest Prof. Dr. Hab. Jagoda Cieszyńska, która pracuje w Uniwersytecie Pedagogicznym w Instytucie Filologii Polskiej, Katedrze Logopedii. Książka obejmuje zagadnienia dotyczące metod diagnozowania oraz problematykę funkcjonowania dzieci z zaburzeniami komunikacji językowej: z autyzmem, z alalią, z afazją, z Zespołem Aspergera, z porażeniem mózgowym oraz obniżeniem sprawności intelektualnej. Jest wspaniałą pozycją wyjaśniającą istotę zjawisk zaburzających prawidłowe funkcjonowanie dziecka oraz przedstawia wiele działań terapeutycznych wspomagających pracę rodziców i pedagogów.
        </h4>
        <h4 class="poletext">W kolejnych miesiącach postaram się przedstawić inne propozycje, które ułatwią Państwu pracę z dziećmi.
        </h4>
        
        </div>
        <div id="zalaczniki">
        <h1>Załączniki</h1>
        <hr width="100%" color="#e84040">
            <h4 class="poletext">Poniżej udostępniam Państwu do pobrania program stymulujący rozwój motoryczny ręki, którego celem jest przekazanie informacji, które skłonią terapeutów i rodziców do podjęcia odpowiednich działań, mających na celu kształtowanie motorycznych funkcji ręki od urodzenia, aż do momentu rysowania i pisania. Opisuje mechanizmy funkcjonowania ruchowego człowieka ze szczególnym uwzględnieniem motoryki ręki. Pokazuje również, jak dokonać prawidłowej diagnozy, a następnie wybrać odpowiednie materiały w postaci wskazówek i ćwiczeń.
            </h4>
            <br>
            <center><a id="program" href="Program stymulujacy rozwoj terapii reki.doc" download>Program stymulujacy rozwoj motoryczny reki.doc</a></center>
            
        </div>
        <div id="koncowka">
            <a class="link" href="test.html"><h5 class="koncoweczka">Wykonane przez Adama Kąkolewskiego 2018</h5></a>
        </div>
        <script src="jquery-3.3.1.min.js"></script>
        <script type="text/javascript">
                $(document).ready(function() {
        var NavY = $('#menugorne').offset().top;
        var stickyNav = function(){
        var ScrollY = $(window).scrollTop();
        if (ScrollY > NavY) { 
            $('#menugorne').addClass('sticky');
        } else {
            $('#menugorne').removeClass('sticky'); 
        }
        };
        stickyNav();
        $(window).scroll(function() {
            stickyNav();
        });
        });
	
        </script>
        
    </body>
</html>
