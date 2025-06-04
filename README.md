# future-project
for future
 {/* Home */}
  <section id="home" className="text-center py-24 bg-blue-100">
    <h2 className="text-4xl font-bold mb-4">未来をつくるマーケティング会社</h2>
    <p className="text-lg text-gray-700 mb-6">あなたのビジネスを次のステージへ。</p>
    <Button className="text-white bg-blue-600 hover:bg-blue-700">今すぐお問い合わせ</Button>
  </section>

  {/* About */}
  <section id="about" className="py-20 px-6 max-w-4xl mx-auto">
    <h3 className="text-3xl font-semibold text-center mb-6">私たちについて</h3>
    <p className="text-gray-700 text-center">
      フューチャー会社は、デジタル時代に最適化されたマーケティング戦略を提供する企業です。
      クライアントのビジネス成長を第一に考え、革新的なアイデアと実行力で成功をサポートします。
    </p>
  </section>

  {/* Services */}
  <section id="services" className="py-20 px-6 bg-gray-100">
    <h3 className="text-3xl font-semibold text-center mb-10">サービス内容</h3>
    <div className="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-6xl mx-auto">
      <Card>
        <CardContent className="p-6">
          <h4 className="text-xl font-bold mb-2">SNSマーケティング</h4>
          <p>Instagram・X・TikTokなどを活用し、ブランド認知度を高めます。</p>
        </CardContent>
      </Card>
      <Card>
        <CardContent className="p-6">
          <h4 className="text-xl font-bold mb-2">SEO対策</h4>
          <p>検索エンジンの上位表示を目指し、オーガニックアクセスを増やします。</p>
        </CardContent>
      </Card>
      <Card>
        <CardContent className="p-6">
          <h4 className="text-xl font-bold mb-2">Web広告運用</h4>
          <p>Google広告やSNS広告を活用し、ターゲットに届く集客を実現します。</p>
        </CardContent>
      </Card>
    </div>
  </section>

  {/* Contact */}
  <section id="contact" className="py-20 px-6 max-w-4xl mx-auto">
    <h3 className="text-3xl font-semibold text-center mb-8">お問い合わせ</h3>
    <div className="space-y-4 text-center">
      <p className="flex justify-center items-center gap-2"><Mail className="w-5 h-5" /> info@future-company.jp</p>
      <p className="flex justify-center items-center gap-2"><Phone className="w-5 h-5" /> 03-1234-5678</p>
      <p className="flex justify-center items-center gap-2"><Globe className="w-5 h-5" /> www.future-company.jp</p>
    </div>
  </section>

  <footer className="text-center py-6 text-gray-500 text-sm">
    © 2025 フューチャー会社. All rights reserved.
  </footer>
</div>
); }
