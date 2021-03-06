# Relay-computers-of-George-Stibitz
>  原文版本[English version](https://history-computer.com/ModernComputer/Relays/Stibitz.html)


<div align=center><img width="200" height="300" src="https://history-computer.com/ModernComputer/Relays/images/stibitz_portrait2.jpg"/></div><br>
Bell Telephone Laboratories成立於1925年，是貝爾系統(Bell System)的基礎研究設施。就這樣建立了一個機構，在frontiers of physics期刊上成為了現代科學前沿基礎研究和有許多令人興奮研究的代名詞。在接下來的幾十年裡，這個實驗室，成為了幾位發明家諾貝爾獎的搖籃。這裡也會在計算機領域做出許多發明，例如first logical schemes with diodes (1942)、 point transistor (1947)、 first fully transistor computer (TRADIC, 1955)、 first modem (1960)、 first single-chip 32-bit processor (1980)、 operating system UNIX (1969)、 programming language C (1973) and C++ (1983)等。<br>
<img src="https://history-computer.com/ModernComputer/Relays/images/ModelKStibitz.jpg" alt="Stibitz's K-Model" width="300" height="268" hspace="5" vspace="0" border="0" align="left"><br>
1937年11月下旬，貝爾實驗室的一位研究數學家喬治·斯蒂布茲（ <a href="https://history-computer.com/People/StibitzBio.html">斯蒂布茲的傳記</a> ）離開工作地點回家，從貝爾儲藏室拿走了兩個電話繼電器，幾個手電筒，以及電線和乾電池。在家裡，他坐在廚房的桌子後面，開始組裝一個簡單的邏輯裝置，該裝置由上述部件和一個由錫罐製成的開關組成。他很快有了一個設備，該設備被證明是第一個繼電器二進制加法器，其中點亮的燈泡表示二進制數字“ 1”，而未點亮的燈泡表示二進制數字“ 0”。他的妻子多蘿西婭（Dorotheea）以“廚房桌子(kitchen table)”命名為K-model。第二天，Stibitz將K-model帶到實驗室向同事展示，他們推測有可能用繼電器構建一個全尺寸的計算器。他的同事認為，任何使用二進制算術的實用繼電器計算機可能都需要數百個繼電器，因此，與當時在實驗室使用的商用機械計算器相比，它既笨重又昂貴。<br><br>
但是，喬治·斯蒂布茲（George Stibitz）意識到，中繼計算器不僅可以執行一個運算，還可以執行一系列計算，而中繼電路可以控制順序並根據需要存儲臨時結果。 具體來說，它可以執行執行複數乘法和除法所需的一系列操作：貝爾實驗室其他地方的研究人員在長距離電路的濾波器和放大器設計中經常執行的兩項數學運算。 在1930年代的實驗室中，一大堆人類“計算機”使用商用機械計算器計算出複數商和乘積。 計算本身非常簡單：複雜的乘法需要大約六個簡單的算術運算，而復雜的除法則需要大約十二個運算，每個運算都需要臨時存儲一些中間結果。<br><br>
斯蒂布茲不知道在柏林，康拉德·祖斯（Konrad Zuse）在同一時間幾乎在做同樣的事情。 然而，斯蒂伯茨確實知道克勞德·香農（Claude Shannon）還在麻省理工學院（MIT）研究生期間也研究了符號邏輯語句與二進制繼電器電路的對應關係。 香農（Shannon）撰寫了有關該主題的研究生論文（於1938年出版），然後去了貝爾實驗室，在那裡他和斯蒂布茲（Stibitz）了解了彼此的工作。 但是香農（Shannon）並未積極參與斯蒂布茲（Stibitz）計算機的設計。 顯然，使用繼電器實現二進制邏輯的想法在1930年代後期很普遍。 （日本也有類似的發現）。<br>
<div align=center><img src="https://history-computer.com/ModernComputer/Relays/images/StibitzTerminalSchema.jpg" alt="Drawing of the teletype of the Complex Number Computer" width="400" height="246"><div><br>
當斯蒂布茲（Stibitz）首次向公司高管展示他的K型計算機(K-model)時，他們並沒有留下深刻的印象。 他後來記得，沒人對他的發明抱有發展的潛力。 然而，不到一年之後，貝爾的高管們改變了對斯蒂布茲（Stibitz）發明的想法。 做出此決定的重要因素是，貝爾尋求解決其日益複雜的數學問題的方法的壓力越來越大。 該公司同意資助斯蒂布茲（Stibitz）發明的大型實驗模型的建設。 斯蒂布茲（Stibitz）於1938年2月完成了設計，該機器的建造工作於1939年4月由貝爾的一位交換工程師Samuel Williams進行。 最終產品在10月準備就緒，並於1940年1月8日首次投入使用 ，一直使用到1949年。隨著貝爾實驗室在戰爭期間建造其他中繼計算機，其名稱從最初的“*Complex Number Computer*”更改為“模型1(Model 1)”。 費用約為2萬美元。<br>
最初，複數計算機僅執行複雜的乘法和除法，但後來進行了簡單的修改，使其也可以進行加法和減法。它使用了大約400-450個二進制繼電器，6-8個面板和10個“multiposition”，多極繼電器來臨時存儲數字。機器使用十進制系統，小數點固定在每個數字的開頭。在內部，四個二進制繼電器對每個數字進行編碼，使用的代碼用n + 3的二進制代碼表示十進制數字n；這簡化了數字進位和減法的問題（今天，多餘的三個二進制編碼的十進制仍稱為“ Stibitz碼”）。機器在其寄存器中處理了十位數的數字，但顯示並打印了八位數的答案（範圍為0.99999999）。它使用“前綴”表示法：也就是說，運算符先將算術運算先鍵入鍵，然後再鍵入操作數。例如，要將兩個複數（2 + 3i）乘以（4 + 5i），操作員將鍵入（請參閱鍵盤的上方圖）：<br>
<strong>M +.2 +i .3 +.4 -i .5 =</strong><br>字母M代表乘法（鍵盤上的字母D代表除法）。 請注意小數點的位置在四個數字中的每個數字之前。 機器實際上將計算（0.3 + 0.5i）x（0.4-0.2i），並輸出答案<em>0.07000000+i 0.22000000</em>。 操作員將不得不相應地縮放結果（乘以100）。 一個簡單的加法運算大約需要100毫秒，而將2個複數相乘大約需要45秒。
<br><img src="https://history-computer.com/ModernComputer/Relays/images/StibitzTerminal.jpg" alt="Stibitz's Terminal" width="200" height="226" hspace="5" vspace="0" border="0" align="left"><br>
<P Align="Left">
計算單元有4個寄存器，並且與作為特殊端子的輸入/輸出單元完全分開（請參見附近的照片）。 計算機本身被保存在實驗室的一間偏僻房間中，很少有人見過。 操作員使用三台經過修改的電傳打字機（鍵盤和打印設備）之一遠程訪問它，該電傳打字機通過多線總線連接到處理器，並放置在其他位置，但是不能同時工作。
</>

斯蒂布茲（Stibitz）進一步發展了遠程，多路訪問計算機的想法。 1940年9月11日，美國數學學會在新罕布什爾州漢諾威的達特茅斯學院會面，它位於紐約貝爾實驗室大樓以北數百英里處，那裡是複數計算機。 斯蒂布茲（Stibitz）安排通過電話線（28線電傳打字電纜）將計算機連接到安裝在其中的電傳打字設備。 複數計算機運行良好，毫無疑問，它給使用它的人留下了深刻的印象。 許多美國最傑出的數學家以及後來領導重要計算項目的個人（例如，約翰·馮·諾伊曼，約翰·莫赫利，諾伯特·維納和加勒特·伯克霍夫）參加了會議。 達特茅斯（Dartmouth）演示預示了遠程計算的現代時代，但是這種類型的遠程訪問再過十年都沒有再次發生。

<img src="https://history-computer.com/ModernComputer/Relays/images/CNCofStibitz.jpg" alt="CNC computer of Stibitz, copyright Lucent Technologies" width="289" height="390" hspace="3" align="left"><br>
<P Align="Left">複數計算機無法編程。 繼電器電路的組合可永久控制其操作順序。 這些繼電器與用於處理數字的繼電器具有相同的類型，但是機器沒有單獨的、定義明確的部分來處理計算序列的“控制”。 （後來的貝爾實驗室計算機採用了這種方法。）只有在復雜數字計算機建成之後，貝爾實驗室才出現了可編程性的概念，因為它的建造者看到其基本計算元素受到其結合的過分限制，無法與控制電路聯繫起來，只能將其與復雜的算術聯繫在一起。（除了複數算法外，他們還嘗試使機器執行多項式算術，其中復數算術是一種特例。但是，這對機器來說太受限制了。）</><br><br>
複數計算機的成功鼓勵了斯蒂布茲（Stibitz）提出更具雄心的設計，其中包括可以通過穿孔的磁帶修改計算器的操作。 起初，實驗室拒絕了他的提議，但隨著美國在1941年12月加入第二次世界大戰，貝爾實驗室將其優先重點轉移到了軍事項目上，該項目所涉及的計算量超過其和平時期的研究。 他們大部分的戰時成就都在模擬計算機的設計中。 但是他們還建造了五台用於軍事目的的數字中繼計算機，並在戰爭結束後又建造了一台供自己使用的數字中繼計算機，從而使總共七台數字計算機計算出了複數計算機。<br><br>
除了編程能力，後來的貝爾計算機還強調了非凡的可靠性。用作邏輯和存儲器操作的基本元素的繼電器有間歇性故障的趨勢。如果在兩個繼電器觸點之間有灰塵積聚，則該電路將發生故障，儘管繼電器的其餘部分運作正常。幾次循環後，灰塵顆粒可能會自行晃動，然後一切恢復正常。因此，整個計算可能會偏離，且在診斷會話期間不會出現任何機器故障。<br><br>
貝爾的工程師設計了計算機電路，可以在計算的每個步驟進行自我檢查。電路的設計不僅要增加，減去，存儲數字等等。他們還被設計為檢查自己是否正確完成了這些操作，否則將機器停止。貝爾的工程師還以其設計電話電路的經驗為指導，這些電話電路必須在經常處於不利環境的情況下長時間無人值守。這些電路設計為由半熟練的技術人員進行維修；如果每次電話線掉線或客戶的電話壞了時都要打電話給工程師，電話服務的成本將非常高。 Bell Labs II至VI模型使用的系統中，每個十進制數字編碼的不是四個而是七個二進制繼電器。它們分為兩組，每組兩個和五個繼電器；十進制代碼如下：<br>
<table>
    <tbody><tr>
        <td width="100"><div align="center">Decimal digit</div></td>
        <td colspan="2"><div align="center">Relays</div></td>
        </tr>
      <tr>
        <td width="100">0</td>
        <td width="150">01</td>
        <td width="200">00001</td>
      </tr>
      <tr>
        <td width="100">1</td>
        <td width="150">01</td>
        <td width="200">00010</td>
      </tr>
      <tr>
        <td width="100">2</td>
        <td width="150">01</td>
        <td width="200">00100</td>
      </tr>
      <tr>
        <td width="100">3</td>
        <td width="150">01</td>
        <td width="200">01000</td>
      </tr>
      <tr>
        <td width="100">4</td>
        <td width="150">01</td>
        <td width="200">10000</td>
      </tr>
      <tr>
        <td width="100">5</td>
        <td width="150">10</td>
        <td width="200">00001</td>
      </tr>
      <tr>
        <td width="100">6</td>
        <td width="150">10</td>
        <td width="200">00010</td>
      </tr>
      <tr>
        <td width="100">7</td>
        <td width="150">10</td>
        <td width="200">00100</td>
      </tr>
      <tr>
        <td width="100">8</td>
        <td width="150">10</td>
        <td width="200">01000</td>
      </tr>
      <tr>
        <td width="100">9</td>
        <td width="150">10</td>
        <td width="200">10000</td>
      </tr>
    </tbody>
</table><br>
<P Align="Left">
貝爾實驗室稱此系統為“二元”表示法，因為繼電器的權重為一或五。 實際上，它不是這些數字基礎的組合； 而是一個七位混合十進制代碼。 所有的貝爾實驗室中繼計算機都以十進制算法工作。 一個特殊的電路檢查發現每個十進制數字有兩個，只有兩個繼電器通電。 另一個電路檢查了每個組中只有一個繼電器的接通狀態，這防止了兩個單獨的錯誤相互抵消，儘管某些異常組合可能無法檢測到。</p><br>
<br>
<P Align="Left">
詞彙                    <br>
institution         機構<br>
synonymous          同義的<br>
schemes	            方案<br>
tobacco tin         錫罐<br>
speculated          推測<br>
relays              繼電器<br>
colleagues          同事<br>
bulkier             笨重<br>
commercial          商用的<br>
interim             臨時的<br>
circuits            電路<br>
straightforward     直截了當<br>
intermediate        中間<br>
correspondence      對應關係<br>
crossbars           多極繼電器<br>
terminal            終端機<br>
prominent           傑出<br>
foreshadowed        預兆<br>
perforated tape     穿孔的磁帶<br>
proposals           提議<br>
shift               轉移<br>
Relay Interpolator  中繼插值器<br>
cement              接合<br>
interpolation       插植<br>
reliability         可靠性<br>
diagnostic          診斷<br></p>
</>
