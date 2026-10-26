[算算脑-隐私政策.html](https://github.com/user-attachments/files/33956542/-.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>算算脑 · 隐私政策</title>
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Crect x='1' y='1' width='22' height='22' rx='6' fill='%23E0813B'/%3E%3Cpath d='M12 5c1.8 0 3.3 1.2 3.3 2.9 0 1.2-.7 1.9-1.6 2.8-.7.7-1.4 1.3-1.4 2.4h-.6c0-1.5.8-2.2 1.6-3 .8-.7 1.4-1.3 1.4-2.2 0-1-.9-1.8-2.2-1.8s-2.2.8-2.2 1.8h-.6C9.5 6.2 10.6 5 12 5z' fill='%23fff'/%3E%3Ccircle cx='12' cy='17.3' r='1.1' fill='%23fff'/%3E%3C/svg%3E">
<style>
  :root{
    --bg:#F6F1E6;
    --card:#FFFFFF;
    --ink:#26303D;
    --sub:#5A6470;
    --accent:#E0813B;
    --accent-soft:#FBE9DA;
    --line:#E7DFCF;
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{-webkit-text-size-adjust:100%}
  body{
    font-family:"PingFang SC","Microsoft YaHei","Hiragino Sans GB",sans-serif;
    background:var(--bg);
    color:var(--ink);
    line-height:1.9;
    -webkit-font-smoothing:antialiased;
  }
  .wrap{max-width:760px;margin:0 auto;padding:22px 18px 56px}

  /* ===== 顶部应用栏 ===== */
  .appbar{
    display:flex;align-items:center;gap:12px;
    padding:14px 18px;
    max-width:760px;margin:0 auto;
  }
  .appbar .logo{
    width:42px;height:42px;flex:none;
    border-radius:11px;
    background:var(--accent);
    display:flex;align-items:center;justify-content:center;
  }
  .appbar .logo svg{width:26px;height:26px}
  .appbar .name{font-size:19px;font-weight:700;color:var(--ink)}
  .appbar .tag{
    margin-left:auto;font-size:13px;color:var(--accent);
    background:var(--accent-soft);
    padding:4px 12px;border-radius:999px;font-weight:600;
  }

  /* ===== 文档头 ===== */
  .doc-head{
    background:var(--card);
    border:1px solid var(--line);
    border-radius:16px;
    padding:28px 22px;
    margin-top:6px;
  }
  .doc-head h1{font-size:27px;line-height:1.35;color:var(--ink);font-weight:800}
  .doc-head .meta{
    margin-top:10px;font-size:14px;color:var(--sub);
    display:flex;flex-wrap:wrap;gap:6px 18px;
  }
  .doc-head .meta b{color:var(--ink);font-weight:600}
  .lead{
    margin-top:16px;font-size:16px;color:var(--ink);
    border-left:4px solid var(--accent);
    padding-left:14px;
  }
  .lead p+p{margin-top:10px}
  .operator{
    margin-top:14px;
    background:var(--accent-soft);
    border-radius:10px;
    padding:10px 14px;
    font-size:15px;
  }
  .operator b{color:var(--accent)}

  /* ===== 章节 ===== */
  section{margin-top:26px}
  .sec-title{
    display:flex;align-items:baseline;gap:12px;
    font-size:20px;font-weight:800;color:var(--ink);
    margin-bottom:12px;
  }
  .sec-title .no{
    font-size:15px;font-weight:700;color:var(--accent);
    background:var(--accent-soft);
    width:30px;height:30px;flex:none;
    border-radius:9px;
    display:inline-flex;align-items:center;justify-content:center;
    align-self:center;
  }
  .card{
    background:var(--card);
    border:1px solid var(--line);
    border-radius:14px;
    padding:20px 22px;
  }
  .card p{font-size:16px;color:var(--ink)}
  .card p+p{margin-top:14px}
  .card .num{
    color:var(--sub);font-size:15px;font-weight:600;
  }
  .card li{margin-left:1.4em;font-size:16px}
  .card li+li{margin-top:10px}

  /* ===== 联系我们 ===== */
  .contact{display:grid;gap:10px}
  .contact .row{
    display:flex;align-items:center;gap:12px;
    background:#FAF6EE;border:1px solid var(--line);
    border-radius:10px;padding:12px 14px;
  }
  .contact .row .k{color:var(--sub);font-size:14px;flex:none;width:84px}
  .contact .row .v{font-size:16px;font-weight:600;color:var(--ink)}
  .contact a.v{color:var(--accent);text-decoration:none}
  .contact a.v:hover{text-decoration:underline}

  /* ===== 法律依据 ===== */
  .laws{counter-reset:law}
  .laws p.law-item{counter-increment:law;padding-left:0;position:relative;margin-top:12px}
  .laws p.law-item::before{
    content:counter(law);
    color:var(--accent);font-weight:700;margin-right:10px;
    font-size:15px;
  }

  /* ===== 页脚 ===== */
  footer{
    margin-top:34px;text-align:center;
    font-size:14px;color:var(--sub);
    padding-top:22px;border-top:1px solid var(--line);
  }

  @media (min-width:768px){
    .wrap{padding-top:30px}
    .doc-head{padding:34px 34px}
    .doc-head h1{font-size:31px}
    .card{padding:24px 30px}
  }
</style>
</head>
<body>
  <div class="appbar">
    <div class="logo">
      <svg viewBox="0 0 24 24" aria-hidden="true"><rect x="1" y="1" width="22" height="22" rx="6" fill="none" stroke="#fff" stroke-width="1.4"/><path d="M12 5c1.8 0 3.3 1.2 3.3 2.9 0 1.2-.7 1.9-1.6 2.8-.7.7-1.4 1.3-1.4 2.4h-.6c0-1.5.8-2.2 1.6-3 .8-.7 1.4-1.3 1.4-2.2 0-1-.9-1.8-2.2-1.8s-2.2.8-2.2 1.8h-.6C9.5 6.2 10.6 5 12 5z" fill="#fff"/><circle cx="12" cy="17.3" r="1.1" fill="#fff"/></svg>
    </div>
    <div class="name">算算脑</div>
    <div class="tag">隐私政策</div>
  </div>

  <div class="wrap">
    <!-- ===== 文档头 ===== -->
    <div class="doc-head">
      <h1>算算脑 隐私政策</h1>
      <div class="meta">
        <span>更新日期：<b>2026年10月26日</b></span>
        <span>生效日期：<b>2026年10月26日</b></span>
      </div>
      <div class="lead">
        <p>本隐私政策（以下简称“本政策”）适用于“算算脑”移动应用（以下简称“本应用”）及其提供的算术练习服务。我们重视您的个人信息保护，并依照《中华人民共和国个人信息保护法》等法律法规的要求，采取相应措施保护您的信息安全。在使用本应用前，请您仔细阅读并理解本政策。如您对本政策有任何疑问，可通过文末“联系我们”所载方式与我们联系。</p>
        <p>本应用由黄永涛（以下统称“我们”）独立开发并运营，为您提供本地算术练习服务。</p>
      </div>
      <div class="operator">运营主体：<b>黄永涛</b> · 联系邮箱：<b>552335138@qq.com</b></div>
    </div>

    <!-- ===== 一 ===== -->
    <section>
      <div class="sec-title"><span class="no">一</span>我们如何收集和使用您的信息</div>
      <div class="card">
        <p><span class="num">（一）</span>本应用为本地离线算术练习工具，不接入互联网，不收集您的任何个人信息。</p>
        <p><span class="num">（二）</span>您无需注册、无需登录即可使用本应用的全部功能，本应用不要求也不获取您的任何身份信息。</p>
        <p><span class="num">（三）</span>本应用不申请任何系统权限，不会读取您的通讯录、位置、相册、麦克风、摄像头等数据。</p>
        <p><span class="num">（四）</span>语音播报功能调用设备系统自带的文字转语音（TTS）能力，仅在本机朗读题目与结果。我们既不采集、也不存储任何音频或语音数据。</p>
        <p><span class="num">（五）</span>本地数据说明：为记录练习进度，本应用会在您的设备本地保存连击数、每日答题数、正确率及错题记录。上述数据仅存储于本机，不传输至任何服务器，卸载本应用后即被清除。</p>
      </div>
    </section>

    <!-- ===== 二 ===== -->
    <section>
      <div class="sec-title"><span class="no">二</span>信息的存储</div>
      <div class="card">
        <p>本应用产生的练习数据仅保存在您的设备本地存储中，不会上传至任何云端服务器，也不会提供给任何第三方。</p>
      </div>
    </section>

    <!-- ===== 三 ===== -->
    <section>
      <div class="sec-title"><span class="no">三</span>未成年人保护</div>
      <div class="card">
        <p>本应用面向儿童及未成年人提供算术练习服务，我们尤其重视对儿童个人信息的保护。本应用不收集儿童的任何个人信息，也不要求儿童提供任何身份信息。我们建议监护人对未成年人使用本应用给予适当的指导与陪伴。如监护人发现本应用存在可能涉及儿童个人信息的任何情形，可按照本政策“联系我们”所载渠道与我们联系。</p>
      </div>
    </section>

    <!-- ===== 四 ===== -->
    <section>
      <div class="sec-title"><span class="no">四</span>第三方服务与 SDK</div>
      <div class="card">
        <p>本应用不包含任何第三方 SDK、广告 SDK、统计 SDK 或分享组件，也不接入任何第三方服务。</p>
      </div>
    </section>

    <!-- ===== 五 ===== -->
    <section>
      <div class="sec-title"><span class="no">五</span>权限说明</div>
      <div class="card">
        <p>本应用不申请任何系统敏感权限，运行本应用无需联网。</p>
      </div>
    </section>

    <!-- ===== 六 ===== -->
    <section>
      <div class="sec-title"><span class="no">六</span>信息的共享、转让与公开披露</div>
      <div class="card">
        <p>本应用不收集个人信息，因此不存在向第三方共享、转让或公开披露个人信息的情形。</p>
      </div>
    </section>

    <!-- ===== 七 ===== -->
    <section>
      <div class="sec-title"><span class="no">七</span>您的权利与数据删除</div>
      <div class="card">
        <p>您可以通过卸载本应用来清除全部本地数据。由于数据仅保存在您的设备上，删除操作完全由您自主控制，无需向任何第三方提出申请。</p>
      </div>
    </section>

    <!-- ===== 八 ===== -->
    <section>
      <div class="sec-title"><span class="no">八</span>本政策的更新</div>
      <div class="card">
        <p>我们可能适时修订本政策。如发生重要变更，我们会在本应用内以适当方式提示您。修订后的政策自发布之日起生效。</p>
      </div>
    </section>

    <!-- ===== 九 ===== -->
    <section>
      <div class="sec-title"><span class="no">九</span>联系我们</div>
      <div class="card contact">
        <p>如您对本政策或本应用的隐私实践有任何疑问、意见或建议，可通过以下方式与我们联系：</p>
        <div class="row"><span class="k">运营主体</span><span class="v">黄永涛</span></div>
        <div class="row"><span class="k">联系邮箱</span><a class="v" href="mailto:552335138@qq.com">552335138@qq.com</a></div>
        <p>我们将在收到您的反馈后及时处理，并尽力在合理期限内予以答复。</p>
      </div>
    </section>

    <!-- ===== 十 ===== -->
    <section>
      <div class="sec-title"><span class="no">十</span>法律依据</div>
      <div class="card laws">
        <p>本应用的设计与运营遵循下列法律法规及标准的要求：</p>
        <p class="law-item">《中华人民共和国个人信息保护法》（2021年11月1日起施行）；</p>
        <p class="law-item">《中华人民共和国网络安全法》（2017年6月1日起施行，2025年修正后于2026年1月1日起施行）；</p>
        <p class="law-item">《中华人民共和国数据安全法》（2021年9月1日起施行）；</p>
        <p class="law-item">《中华人民共和国民法典》（2021年1月1日起施行，其人格权编对隐私权予以保护）；</p>
        <p class="law-item">《儿童个人信息网络保护规定》（国家互联网信息办公室令第4号，2019年10月1日起施行）；</p>
        <p class="law-item">《信息安全技术 个人信息安全规范》（GB/T 35273-2020）。</p>
      </div>
    </section>

    <footer>感谢您使用“算算脑”。本政策于 2026 年 10 月 26 日发布。</footer>
  </div>
</body>
</html>
