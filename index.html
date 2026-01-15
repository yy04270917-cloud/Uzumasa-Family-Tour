import React, { useState } from 'react';
import { Clock, MapPin, Camera, Train, Umbrella, Sun, Coffee, Star, Info, ChevronDown, ChevronUp, AlertCircle } from 'lucide-react';

const PlanStep = ({ time, title, description, icon: Icon, tags }) => (
  <div className="flex gap-4 mb-8 relative">
    <div className="flex flex-col items-center">
      <div className="w-12 h-12 rounded-full bg-red-600 flex items-center justify-center text-white z-10 shadow-lg shrink-0">
        {Icon ? <Icon size={24} /> : <Star size={24} />}
      </div>
      <div className="h-full w-1 bg-gray-200 absolute top-12 left-6 -translate-x-1/2 -z-0"></div>
    </div>
    <div className="bg-white rounded-xl p-5 shadow-md flex-1 border-l-4 border-red-500 hover:shadow-lg transition-shadow">
      <div className="flex flex-wrap items-baseline gap-2 mb-2">
        <span className="font-bold text-red-600 text-lg">{time}</span>
        <h3 className="font-bold text-xl text-gray-800">{title}</h3>
      </div>
      <p className="text-gray-600 mb-3 leading-relaxed">{description}</p>
      {tags && (
        <div className="flex flex-wrap gap-2">
          {tags.map((tag, idx) => (
            <span key={idx} className="bg-orange-100 text-orange-800 text-xs px-2 py-1 rounded-full font-medium">
              {tag}
            </span>
          ))}
        </div>
      )}
    </div>
  </div>
);

const TipCard = ({ title, items, icon: Icon }) => (
  <div className="bg-white rounded-xl p-6 shadow-md border border-gray-100 h-full">
    <div className="flex items-center gap-3 mb-4">
      <div className="p-3 bg-indigo-100 rounded-lg text-indigo-600">
        <Icon size={24} />
      </div>
      <h3 className="font-bold text-lg text-gray-800">{title}</h3>
    </div>
    <ul className="space-y-3">
      {items.map((item, idx) => (
        <li key={idx} className="flex items-start gap-2 text-gray-600 text-sm">
          <span className="text-indigo-400 mt-1">•</span>
          <span>{item}</span>
        </li>
      ))}
    </ul>
  </div>
);

const Accordion = ({ title, children, isOpen, onClick }) => (
  <div className="border border-gray-200 rounded-lg overflow-hidden mb-3 bg-white">
    <button
      className="w-full flex items-center justify-between p-4 bg-gray-50 hover:bg-gray-100 transition-colors"
      onClick={onClick}
    >
      <span className="font-bold text-gray-700">{title}</span>
      {isOpen ? <ChevronUp size={20} className="text-gray-500" /> : <ChevronDown size={20} className="text-gray-500" />}
    </button>
    {isOpen && <div className="p-4 border-t border-gray-200">{children}</div>}
  </div>
);

const App = () => {
  const [activeTab, setActiveTab] = useState('sunny'); // 'sunny' or 'rainy'
  const [openAccordion, setOpenAccordion] = useState(0);

  return (
    <div className="min-h-screen bg-orange-50 font-sans text-gray-800 pb-12">
      {/* Hero Section */}
      <header className="relative h-80 bg-slate-900 flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 opacity-40">
           {/* Abstract background pattern representing motion/movies */}
           <div className="w-full h-full bg-gradient-to-r from-red-900 to-slate-900"></div> 
        </div>
        <div className="relative z-10 text-center px-4 max-w-4xl mx-auto">
          <div className="inline-block bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full mb-3 tracking-wider">
            京都市右京区・太秦エリア
          </div>
          <h1 className="text-3xl md:text-5xl font-extrabold text-white mb-4 leading-tight">
            5歳＆8歳と行く！<br className="md:hidden" />
            <span className="text-yellow-400">忍者</span>と<span className="text-purple-400">電車</span>の<br />
            わくわく冒険プラン
          </h1>
          <p className="text-gray-300 text-sm md:text-lg max-w-2xl mx-auto">
            映画の世界でヒーローになりきり、レトロな嵐電で冒険へ。<br/>
            車移動でらくらく、家族全員が大満足の1日コース。
          </p>
        </div>
      </header>

      <main className="max-w-3xl mx-auto px-4 -mt-10 relative z-20">
        
        {/* Weather Toggle */}
        <div className="bg-white rounded-2xl shadow-lg p-2 flex mb-8 mx-auto max-w-sm">
          <button
            onClick={() => setActiveTab('sunny')}
            className={`flex-1 flex items-center justify-center gap-2 py-3 rounded-xl font-bold transition-all ${
              activeTab === 'sunny' 
                ? 'bg-orange-500 text-white shadow-md' 
                : 'text-gray-500 hover:bg-gray-100'
            }`}
          >
            <Sun size={20} />
            晴れの日プラン
          </button>
          <button
            onClick={() => setActiveTab('rainy')}
            className={`flex-1 flex items-center justify-center gap-2 py-3 rounded-xl font-bold transition-all ${
              activeTab === 'rainy' 
                ? 'bg-blue-600 text-white shadow-md' 
                : 'text-gray-500 hover:bg-gray-100'
            }`}
          >
            <Umbrella size={20} />
            雨の日プラン
          </button>
        </div>

        {/* Itinerary Section */}
        {activeTab === 'sunny' ? (
          <div className="animate-fade-in">
            <h2 className="text-2xl font-bold text-center mb-8 text-gray-800 flex items-center justify-center gap-2">
              <span className="w-8 h-1 bg-red-500 rounded-full"></span>
              冒険のスケジュール
              <span className="w-8 h-1 bg-red-500 rounded-full"></span>
            </h2>

            <div className="pl-2">
              <PlanStep 
                time="09:30" 
                title="映画村到着・駐車場へ" 
                description="車を映画村駐車場または近隣のコインパーキングへ。冒険の準備はOK？"
                icon={MapPin}
                tags={['車移動', '駐車場']}
              />
              <PlanStep 
                time="10:00" 
                title="「ちびっこ忍者」に変身！" 
                description="入村してすぐに「時代劇扮装の館」へ。衣装のまま村内を歩けるので、最高に映える写真が撮れます。"
                icon={Camera}
                tags={['体験：着付け', '記念撮影']}
              />
              <PlanStep 
                time="10:30" 
                title="忍者修行 & アトラクション" 
                description="「からくり忍者屋敷」で隠し通路を探せ！「立体迷路 忍者の砦」で頂上を目指せ！5歳も8歳も夢中です。"
                icon={Star}
                tags={['体験：忍者', '体を使う']}
              />
              <PlanStep 
                time="11:30" 
                title="大迫力！激突忍者ショー" 
                description="3Dマッピングとスタントマンのアクションは圧巻。大人が見ても「おぉ〜！」と声が出る迫力です。"
                icon={AlertCircle}
                tags={['メインスポット', '必見']}
              />
              <PlanStep 
                time="12:30" 
                title="雰囲気満点のランチ" 
                description="村内の「スターズカフェチャンバラ」で忍者カレー？それとも徒歩すぐの「うどん処 嵐山亭」でゆったり京うどん？"
                icon={Coffee}
                tags={['キッズメニューあり', '休憩']}
              />
              <PlanStep 
                time="14:00" 
                title="嵐電（らんでん）プチ冒険" 
                description="車は置いて、徒歩5分の「太秦広隆寺駅」へ。紫色の可愛い路面電車に乗って嵐山へGO！一番前の席が特等席です。"
                icon={Train}
                tags={['体験：嵐電', '路面電車']}
              />
              <PlanStep 
                time="14:30" 
                title="嵐山駅で食べ歩きタイム" 
                description="「キモノフォレスト」で写真を撮ったら、湯葉チーズ串やソフトクリームでおやつタイム。1時間ほど楽しんで太秦へ戻ります。"
                icon={MapPin}
                tags={['食べ歩き', 'スイーツ']}
              />
            </div>
          </div>
        ) : (
          <div className="animate-fade-in space-y-6">
             <div className="bg-blue-50 border border-blue-200 rounded-xl p-6 text-center">
               <h3 className="text-xl font-bold text-blue-800 mb-2">雨でも大丈夫！</h3>
               <p className="text-blue-700">
                 太秦エリアは雨でも楽しめるスポットが充実しています。<br/>
                 お子様の興味に合わせてプランを選んでみてください。
               </p>
             </div>

             <div className="grid gap-4">
                <div className="bg-white p-5 rounded-xl shadow border-l-4 border-purple-500">
                  <h4 className="font-bold text-lg mb-2">プランA：そのまま映画村</h4>
                  <p className="text-gray-600 text-sm">
                    忍者屋敷、お化け屋敷、アニメミュージアム、立体迷路はすべて屋内！
                    ショーも屋内会場なので、雨に濡れずに十分楽しめます。雨の江戸の町並みも情緒たっぷり。
                  </p>
                </div>
                <div className="bg-white p-5 rounded-xl shadow border-l-4 border-indigo-500">
                  <h4 className="font-bold text-lg mb-2">プランB：京都鉄道博物館（車で20分）</h4>
                  <p className="text-gray-600 text-sm">
                    完全に屋内メインの鉄板スポット。本物のSLや新幹線、運転シミュレーターがあり、
                    5歳・8歳のお子様なら一日中夢中で遊べます。
                  </p>
                </div>
                <div className="bg-white p-5 rounded-xl shadow border-l-4 border-cyan-500">
                  <h4 className="font-bold text-lg mb-2">プランC：京都水族館</h4>
                  <p className="text-gray-600 text-sm">
                    鉄道博物館のすぐ隣。イルカショーの客席には屋根があり安心。
                    オオサンショウウオなどユニークな展示が多く、学びながら楽しめます。
                  </p>
                </div>
             </div>
          </div>
        )}

        {/* Tips Section */}
        <section className="mt-12 mb-12">
          <h2 className="text-2xl font-bold text-center mb-8 text-gray-800">
            パパ・ママ必見！<br/><span className="text-red-600">旅の裏技＆ポイント</span>
          </h2>
          
          <div className="grid md:grid-cols-2 gap-6">
            <TipCard 
              title="効率よく回るコツ" 
              icon={Star}
              items={[
                "入村したらまず「ショーの時間」を確認！それを軸に行動計画を。",
                "対象アトラクションを複数回るなら「わくわくチケット」がお得。",
                "入口付近は混みます。朝イチは一番奥のエリアから攻めるのが鉄則！",
                "江戸の町を歩くお侍さんには気軽に声をかけて記念撮影を。"
              ]}
            />
            <TipCard 
              title="周辺の穴場スポット" 
              icon={MapPin}
              items={[
                "蚕ノ社駅周辺：駅のすぐ東側から路面区間になります。大きな電車が車と一緒に走る姿は必見！",
                "蜂ケ丘公園（はちがおかこうえん）：映画村のすぐ近く。ブランコや滑り台などの遊具があり、気分転換に最適。",
                "ジオラマ京都JAPAN：車で15分。鉄道好きなお子様には天国のような場所。"
              ]}
            />
          </div>
        </section>

        {/* FAQ Section */}
        <section className="mb-12">
           <h2 className="text-xl font-bold mb-4 text-gray-700">よくある質問</h2>
           <Accordion 
             title="ベビーカーでの移動は大変ですか？" 
             isOpen={openAccordion === 0}
             onClick={() => setOpenAccordion(openAccordion === 0 ? -1 : 0)}
           >
             <p className="text-gray-600 text-sm">映画村内は平坦な場所が多く、ベビーカーでも比較的スムーズに移動できます。ただし、アトラクション内や一部のセット内には入れないため、ベビーカー置き場を利用する必要があります。</p>
           </Accordion>
           <Accordion 
             title="食事の待ち時間はどのくらい？" 
             isOpen={openAccordion === 1}
             onClick={() => setOpenAccordion(openAccordion === 1 ? -1 : 1)}
           >
             <p className="text-gray-600 text-sm">休日のランチタイム（12:00〜13:00）は村内のレストランが混雑します。11:30頃に早めに入店するか、少し時間をずらすのがおすすめです。再入場スタンプを押してもらえば、一旦外に出て食事をすることも可能です。</p>
           </Accordion>
        </section>

        {/* Footer / CTA */}
        <div className="bg-slate-800 text-white rounded-2xl p-8 text-center shadow-xl">
          <h3 className="text-2xl font-bold mb-2">準備はいいですか？</h3>
          <p className="text-gray-400 mb-6">お子様の笑顔があふれる最高の1日になりますように。</p>
          <div className="flex flex-col md:flex-row gap-4 justify-center">
            <button className="bg-red-600 hover:bg-red-700 text-white font-bold py-3 px-6 rounded-lg shadow transition-colors w-full md:w-auto">
              映画村公式サイトを見る
            </button>
            <button className="bg-white hover:bg-gray-100 text-slate-800 font-bold py-3 px-6 rounded-lg shadow transition-colors w-full md:w-auto">
              嵐電の時刻表をチェック
            </button>
          </div>
        </div>

      </main>

      <footer className="text-center text-gray-400 text-sm mt-12 pb-4">
        © 2024 Uzumasa Family Concierge
      </footer>
    </div>
  );
};

export default App;
