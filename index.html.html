<!doctype html>
<html lang="ko">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<title>교리도 빈칸 퀴즈</title>

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&family=Noto+Serif+KR:wght@500;700&display=swap">
<style>
:root{
  --bg:#eef2ef; --paper:#fffefb; --ink:#16130f; --muted:#5a6a62; --line:#c3d6cc; --card:#ffffff;
  --blank:#ffb8f0; --blank-ink:#6d1f66; --ok:#bde9c8; --ok-ink:#14502a;
  --show:#ffe2b3; --show-ink:#6a4208; --accent:#b02a73; --accent-ink:#ffffff; --bad:#c0392b; --good:#14702f;
  --z1:#fff3c9; --z2:#d9efff; --z3:#e2f5d6; --z4:#fde0e0; --z5:#e8defa; --z6:#ffd9c2; --z7:#d3f1ee; --z8:#f3d9f5; --z9:#e4e9b5;
  --sans:'Noto Sans KR',system-ui,-apple-system,'Apple SD Gothic Neo','Malgun Gothic',sans-serif;
  --serif:'Noto Serif KR','Batang','Apple Myungjo',serif;
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --bg:#0f1512; --paper:#1b1d1c; --ink:#ebe7df; --muted:#9bb0a6; --line:#2d3a34; --card:#1b1d1c;
    --blank:#7a3475; --blank-ink:#ffe0fb; --ok:#1f5a37; --ok-ink:#c9f5d6;
    --show:#6a4a1c; --show-ink:#ffe6bd; --accent:#ff8fcf; --accent-ink:#2a0c1c; --bad:#ff8a7a; --good:#8fe0a8;
    --z1:#3a3317; --z2:#1b3345; --z3:#243a1d; --z4:#442426; --z5:#32284a; --z6:#4a2f1c; --z7:#1b3b3a; --z8:#432a46; --z9:#3b3f1a; color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#0f1512; --paper:#1b1d1c; --ink:#ebe7df; --muted:#9bb0a6; --line:#2d3a34; --card:#1b1d1c;
  --blank:#7a3475; --blank-ink:#ffe0fb; --ok:#1f5a37; --ok-ink:#c9f5d6;
  --show:#6a4a1c; --show-ink:#ffe6bd; --accent:#ff8fcf; --accent-ink:#2a0c1c; --bad:#ff8a7a; --good:#8fe0a8;
  --z1:#3a3317; --z2:#1b3345; --z3:#243a1d; --z4:#442426; --z5:#32284a; --z6:#4a2f1c; --z7:#1b3b3a; --z8:#432a46; --z9:#3b3f1a; color-scheme:dark;
}
*{box-sizing:border-box}
body{
  background:var(--bg); color:var(--ink); font-family:var(--sans); font-size:15px; line-height:1.5;
  padding-left:max(16px,env(safe-area-inset-left,0px)); padding-right:max(16px,env(safe-area-inset-right,0px));
  padding-block:10px 40px;
}
.wrap{max-width:460px;margin:0 auto;display:flex;flex-direction:column;gap:12px}
h1{font-family:var(--serif);font-size:1.35rem;font-weight:700;margin:6px 0 0;text-wrap:balance}
.sub{color:var(--muted);font-size:.85rem;margin:0}

.panel{
  position:sticky; top:env(safe-area-inset-top,0px); z-index:5;
  background:var(--card); border:1.5px solid var(--ink); border-radius:10px; padding:10px 12px;
  display:flex; flex-direction:column; gap:8px;
}
.row{display:flex;align-items:center;justify-content:space-between;gap:10px;min-width:0}
.dots{display:flex;gap:6px}
.dot{width:24px;height:24px;border-radius:50%;border:1.5px solid var(--ink);font-size:.72rem;display:grid;place-items:center;font-weight:700}
.dot.ok{background:var(--ok);color:var(--ok-ink)}
.dot.shown{background:var(--show);color:var(--show-ink)}
.dot.now{outline:2.5px solid var(--accent);outline-offset:1px}
.score{font-size:.85rem;color:var(--muted);font-variant-numeric:tabular-nums;white-space:nowrap}
.where{font-size:.85rem;min-width:0}
.where b{font-weight:700}
form{display:flex;gap:8px}
#ans{flex:1;min-width:0;font:inherit;font-size:18px;padding:10px 12px;border-radius:8px;border:1.5px solid var(--ink);background:var(--paper);color:var(--ink)}
#ans:focus-visible{outline:3px solid var(--accent);outline-offset:1px}
button{font:inherit;cursor:pointer;color:inherit}
.go{border:0;background:var(--accent);color:var(--accent-ink);font-weight:700;border-radius:8px;padding:0 18px;min-height:44px}
.go:focus-visible,.ghost:focus-visible,.blank:focus-visible,.again:focus-visible{outline:3px solid var(--accent);outline-offset:2px}
.msg{font-size:.85rem;min-height:1.3em;color:var(--muted)}
.msg.bad{color:var(--bad);font-weight:500}
.msg.good{color:var(--good);font-weight:500}
.ghost{background:none;border:1px solid var(--line);border-radius:8px;padding:4px 10px;font-size:.8rem;color:var(--muted)}

/* 도표 */
.board{
  background:var(--paper); color:var(--ink); border-radius:6px; padding:12px 6px 10px;
  font-family:var(--serif); font-weight:500; font-size:clamp(12px,3.3vw,16px); line-height:1.25;
}
.crown{display:flex;justify-content:center}
.crown svg{width:6.5em;height:auto;color:var(--ink);display:block}
.frame{display:grid;grid-template-columns:auto minmax(0,1fr) auto;gap:.3em;margin-top:-.1em}
.arm{display:flex;flex-direction:column;justify-content:space-between;gap:.6em;padding-block:.1em}
.side{border:2px solid var(--ink);padding:.5em .3em;writing-mode:vertical-rl;letter-spacing:.2em;font-size:1.05em;font-weight:700}
.arm .side:first-child{align-self:flex-start}
.arm .side:last-child{align-self:flex-end}

.body{
  display:grid;grid-template-columns:1fr 1.05fr 1fr;grid-template-rows:auto auto auto auto;
  gap:2px;background:var(--ink);border:2px solid var(--ink)
}
.cell{background:var(--paper);min-width:0;position:relative}
.z1{background:var(--z1)}.z2{background:var(--z2)}.z3{background:var(--z3)}.z4{background:var(--z4)}.z5{background:var(--z5)}.z6{background:var(--z6)}.z7{background:var(--z7)}.z8{background:var(--z8)}.z9{background:var(--z9)}
.zn{position:absolute;top:1px;left:3px;font-size:.62em;font-family:var(--sans);font-weight:700;opacity:.75;line-height:1}
.hd{text-align:center;padding:.5em .2em .4em;font-weight:700;line-height:1.35}
.hd small{display:block;font-size:.95em;font-weight:500}
.hd b{display:block;letter-spacing:.35em;padding-left:.35em}
.sec{display:flex;flex-direction:column}
.t{display:flex;justify-content:space-between;padding:.25em .7em;border-bottom:1.5px dashed var(--ink);font-weight:700;min-height:2.1em;align-items:center;gap:.4em}
.t.c{justify-content:center;letter-spacing:.05em}
.items{flex:1;display:flex;flex-direction:row-reverse;justify-content:center;align-items:flex-start;padding:.7em .3em}
.ln{writing-mode:vertical-rl;margin:0 .35em;letter-spacing:.12em;white-space:nowrap}
.items.tall{padding:.9em .3em}
.eight{flex:1;display:grid;direction:rtl;grid-template-columns:repeat(4,1fr);align-content:center;gap:.6em .2em;padding:.6em .3em;text-align:center}
.eight>span{direction:ltr;min-height:1.7em;display:flex;justify-content:center;align-items:center;white-space:nowrap}
.cap{text-align:center;font-family:var(--serif);font-weight:700;letter-spacing:.5em;font-size:1.4em;margin-top:.4em;padding-left:.5em}
.cap i{display:block;width:8em;max-width:60%;height:2.5px;background:var(--ink);margin:.2em auto 0}

.legend{display:flex;flex-wrap:wrap;gap:6px 10px;font-size:.72rem;color:var(--muted);margin:0;padding:0;list-style:none}
.legend li{display:flex;align-items:center;gap:5px}
.legend i{width:12px;height:12px;border:1px solid var(--ink);display:inline-block}

/* 빈칸 */
.tk{display:inline}
.blank{
  border:0;background:var(--blank);color:var(--blank-ink);font-family:var(--serif);font-weight:700;font-size:1em;
  border-radius:2px;padding:0;display:inline-flex;align-items:center;justify-content:center;
  touch-action:manipulation;letter-spacing:.05em;vertical-align:middle;outline:1px solid var(--ink);
}
.blank.v{writing-mode:vertical-rl;width:1.5em}
.blank.h{height:1.6em;padding:0 .2em}
.blank.active{box-shadow:0 0 0 2.5px var(--accent);animation:pulse 1.4s ease-in-out infinite}
.blank.ok{background:var(--ok);color:var(--ok-ink);animation:none}
.blank.shown{background:var(--show);color:var(--show-ink);animation:none}
.blank.shake{animation:shake .35s}
@keyframes pulse{50%{box-shadow:0 0 0 5px color-mix(in srgb,var(--accent) 35%,transparent)}}
@keyframes shake{25%{transform:translateX(-3px)}75%{transform:translateX(3px)}}
@media (prefers-reduced-motion:reduce){.blank.active,.blank.shake{animation:none}}

.result{background:var(--card);border:1.5px solid var(--ink);border-radius:10px;padding:14px;display:flex;flex-direction:column;gap:10px}
.result h2{margin:0;font-family:var(--serif);font-size:1.15rem}
.result p{margin:0;color:var(--muted);font-size:.9rem}
.again{border:0;background:var(--accent);color:var(--accent-ink);font-weight:700;border-radius:8px;min-height:46px}
.note{font-size:.75rem;color:var(--muted);margin:0}
</style>
</head>
<body>


<div class="wrap">
  <div>
    <h1>교리도 빈칸 퀴즈</h1>
    <p class="sub">교리도를 다섯 구간으로 나누어 구간마다 한 문제씩 나옵니다. 네 귀퉁이는 가끔 한 구간을 대신해 나옵니다. 분홍 빈칸을 누르고 답을 쓰세요.</p>
  </div>

  <div class="panel">
    <div class="row">
      <div class="dots" id="dots" aria-label="구간별 진행 상황"></div>
      <div class="score" id="score">정답 0 / 5</div>
    </div>
    <div class="where" id="where">빈칸을 눌러 시작하세요</div>
    <form id="form" autocomplete="off">
      <input id="ans" type="text" lang="ko" inputmode="text" enterkeyhint="done" autocomplete="off" autocapitalize="none" autocorrect="off" spellcheck="false" placeholder="정답 입력" aria-label="정답 입력">
      <button class="go" type="submit">확인</button>
    </form>
    <div class="row">
      <div class="msg" id="msg" role="status" aria-live="polite"></div>
      <button class="ghost" type="button" id="show">정답 보기</button>
    </div>
  </div>

  <div class="board" id="board">
    <div class="crown">
      <svg viewBox="0 0 120 96" fill="none" stroke="currentColor" aria-hidden="true">
        <ellipse cx="60" cy="34" rx="37" ry="28" stroke-width="9"/>
        <line x1="8" y1="74" x2="112" y2="74" stroke-width="3"/>
        <line x1="56" y1="74" x2="56" y2="96" stroke-width="2.5"/>
        <line x1="64" y1="74" x2="64" y2="96" stroke-width="2.5"/>
      </svg>
    </div>

    <div class="frame">
      <div class="arm">
        <div class="side z6"><span class="tk" data-z="6" data-o="v" data-h="왼쪽 위 네모 · 은혜를 갚는 것">지은보은</span></div>
        <div class="side z6"><span class="tk" data-z="6" data-o="v" data-h="왼쪽 아래 네모 · 나를 없애고 공을 받드는 것">무아봉공</span></div>
      </div>

      <div class="body">
        <!-- 구간 2 : 신앙문 위 -->
        <div class="cell hd z2" style="grid-column:1;grid-row:1"><span class="zn">②</span>
          <small><span class="tk" data-z="2" data-o="h" data-h="신앙문 위 · 머리글">인과보응의</span></small>
          <b><span class="tk" data-z="2" data-o="h" data-h="왼쪽 큰 제목 (믿음의 문)">신앙문</span></b>
        </div>
        <!-- 구간 1 : 중앙 -->
        <div class="cell sec z1" style="grid-column:2;grid-row:1 / 3"><span class="zn">①</span>
          <div class="items tall">
            <span class="ln">일원은 <span class="tk" data-z="1" data-o="v" data-h="일원은 ○○이니 · 불(佛)의 몸">법신불</span>이니</span>
            <span class="ln">우주만유의 <span class="tk" data-z="1" data-o="v" data-h="우주만유의 ○○이요 · 뿌리">본원</span>이요</span>
            <span class="ln">제불제성의 <span class="tk" data-z="1" data-o="v" data-h="제불제성의 ○○이요 · 마음 도장">심인</span>이요</span>
            <span class="ln">일체중생의 <span class="tk" data-z="1" data-o="v" data-h="일체중생의 ○○이다 · 타고난 성품">본성</span>이다.</span>
          </div>
        </div>
        <!-- 구간 4 : 수행문 위 -->
        <div class="cell hd z4" style="grid-column:3;grid-row:1"><span class="zn">④</span>
          <small><span class="tk" data-z="4" data-o="h" data-h="수행문 위 · 머리글">진공묘유의</span></small>
          <b><span class="tk" data-z="4" data-o="h" data-h="오른쪽 큰 제목 (닦는 문)">수행문</span></b>
        </div>

        <div class="cell sec z2" style="grid-column:1;grid-row:2"><span class="zn">②</span>
          <div class="t"><span class="tk" data-z="2" data-o="h" data-h="신앙문 · 네 가지 은혜" data-a="사은">사 은</span></div>
          <div class="items" style="min-height:7.2em">
            <span class="ln"><span class="tk" data-z="2" data-o="v" data-h="사은 · 하늘과 땅의 은혜">천지은</span></span>
            <span class="ln"><span class="tk" data-z="2" data-o="v" data-h="사은 · 어버이의 은혜">부모은</span></span>
            <span class="ln"><span class="tk" data-z="2" data-o="v" data-h="사은 · 함께 사는 이들의 은혜">동포은</span></span>
            <span class="ln"><span class="tk" data-z="2" data-o="v" data-h="사은 · 나라와 법의 은혜">법률은</span></span>
          </div>
        </div>
        <div class="cell sec z4" style="grid-column:3;grid-row:2"><span class="zn">④</span>
          <div class="t"><span class="tk" data-z="4" data-o="h" data-h="수행문 · 세 가지 공부" data-a="삼학">삼 학</span></div>
          <div class="items" style="min-height:7.2em">
            <span class="ln"><span class="tk" data-z="4" data-o="v" data-h="삼학 첫째 · 마음을 닦음">정신수양</span></span>
            <span class="ln"><span class="tk" data-z="4" data-o="v" data-h="삼학 둘째 · 이치를 연마함">사리연구</span></span>
            <span class="ln"><span class="tk" data-z="4" data-o="v" data-h="삼학 셋째 · 취하고 버림">작업취사</span></span>
          </div>
        </div>

        <!-- 구간 3 : 신앙문 아래 -->
        <div class="cell sec z3" style="grid-column:1;grid-row:3"><span class="zn">③</span>
          <div class="t"><span class="tk" data-z="3" data-o="h" data-h="신앙문 · 네 가지 요법" data-a="사요">사 요</span></div>
          <div class="items" style="min-height:7.6em">
            <span class="ln"><span class="tk" data-z="3" data-o="v" data-h="사요 · 스스로 힘을 기름">자력양성</span></span>
            <span class="ln"><span class="tk" data-z="3" data-o="v" data-h="사요 · 지혜 있는 사람이 본위가 됨">지자본위</span></span>
            <span class="ln"><span class="tk" data-z="3" data-o="v" data-h="사요 · 남의 자녀를 가르침">타자녀교육</span></span>
            <span class="ln"><span class="tk" data-z="3" data-o="v" data-h="사요 · 공도 가진 사람을 숭배함">공도자숭배</span></span>
          </div>
        </div>
        <!-- 구간 1 : 계송 -->
        <div class="cell sec z1" style="grid-column:2;grid-row:3 / 5"><span class="zn">①</span>
          <div class="t"><span>계</span><span>송</span></div>
          <div class="items tall">
            <span class="ln">유는 무로 무는 유로</span>
            <span class="ln">돌고 돌아 지극하면</span>
            <span class="ln">유와 무가 <span class="tk" data-z="1" data-o="v" data-h="계송 셋째 줄 · 유와 무가 ○○이나 · 모두 비었다">구공</span>이나</span>
            <span class="ln">구공 역시 <span class="tk" data-z="1" data-o="v" data-h="계송 끝줄 · 구공 역시 ○○이라 · 모두 갖추었다">구족</span>이라.</span>
          </div>
        </div>
        <!-- 구간 5 : 수행문 아래 -->
        <div class="cell sec z5" style="grid-column:3;grid-row:3"><span class="zn">⑤</span>
          <div class="t"><span class="tk" data-z="5" data-o="h" data-h="수행문 · 여덟 가지 조목" data-a="팔조">팔 조</span></div>
          <div class="eight" style="min-height:7.6em">
            <span><span class="tk" data-z="5" data-o="h" data-h="팔조 · 진행사조 첫째">신</span></span>
            <span><span class="tk" data-z="5" data-o="h" data-h="팔조 · 진행사조 둘째">분</span></span>
            <span><span class="tk" data-z="5" data-o="h" data-h="팔조 · 진행사조 셋째">의</span></span>
            <span><span class="tk" data-z="5" data-o="h" data-h="팔조 · 진행사조 넷째">성</span></span>
            <span><span class="tk" data-z="5" data-o="h" data-h="팔조 · 사연사조 첫째">불신</span></span>
            <span><span class="tk" data-z="5" data-o="h" data-h="팔조 · 사연사조 둘째" data-alt="탐">탐욕</span></span>
            <span><span class="tk" data-z="5" data-o="h" data-h="팔조 · 사연사조 셋째" data-alt="나태">나</span></span>
            <span><span class="tk" data-z="5" data-o="h" data-h="팔조 · 사연사조 넷째" data-alt="우치">우</span></span>
          </div>
        </div>

        <div class="cell sec z3" style="grid-column:1;grid-row:4"><span class="zn">③</span>
          <div class="t c"><span class="tk" data-z="3" data-o="h" data-h="왼쪽 아래 제목 · 은혜 갚는 것이 곧 ○○">보은즉불공</span></div>
          <div class="items" style="min-height:6.6em">
            <span class="ln"><span class="tk" data-z="3" data-o="v" data-h="보은즉불공 · 어디에나 부처님">처처불상</span></span>
            <span class="ln"><span class="tk" data-z="3" data-o="v" data-h="보은즉불공 · 모든 일이 불공">사사불공</span></span>
          </div>
        </div>
        <div class="cell sec z5" style="grid-column:3;grid-row:4"><span class="zn">⑤</span>
          <div class="t c"><span class="tk" data-z="5" data-o="h" data-h="오른쪽 아래 제목 · 움직일 때나 고요할 때나 떠나지 않는 선">동정간불리선</span></div>
          <div class="items" style="min-height:6.6em">
            <span class="ln"><span class="tk" data-z="5" data-o="v" data-h="동정간불리선 · 때를 가리지 않는 선">무시선</span></span>
            <span class="ln"><span class="tk" data-z="5" data-o="v" data-h="동정간불리선 · 곳을 가리지 않는 선">무처선</span></span>
          </div>
        </div>
      </div>

      <div class="arm">
        <div class="side z6"><span class="tk" data-z="6" data-o="v" data-h="오른쪽 위 네모 · 바르게 깨닫고 바르게 행함">정각정행</span></div>
        <div class="side z6"><span class="tk" data-z="6" data-o="v" data-h="오른쪽 아래 네모 · 불법을 생활에 씀">불법활용</span></div>
      </div>
    </div>

    <div class="cap">교리도<i></i></div>
  </div>

  <ul class="legend" aria-label="구간 안내">
    <li><i style="background:var(--z1)"></i>① 중앙</li>
    <li><i style="background:var(--z2)"></i>② 신앙문 위</li>
    <li><i style="background:var(--z3)"></i>③ 신앙문 아래</li>
    <li><i style="background:var(--z4)"></i>④ 수행문 위</li>
    <li><i style="background:var(--z5)"></i>⑤ 수행문 아래</li>
    <li><i style="background:var(--z6)"></i>⑥ 네 귀퉁이(5번 중 2번)</li>
  </ul>

  <div id="result" class="result" hidden>
    <h2 id="rtitle"></h2>
    <p id="rtext"></p>
    <button class="again" type="button" id="again">새 문제 5개 만들기</button>
  </div>

  <div class="row">
    <button class="ghost" type="button" id="reset">다른 5문제로 바꾸기</button>
  </div>
  <p class="note">띄어쓰기는 구분하지 않습니다. 문제는 항상 5개입니다. 네 귀퉁이(지은보은·정각정행·무아봉공·불법활용) 문제는 새 문제 5번 중 2번만, 그때도 1문제만 나옵니다.</p>
</div>

<script>
(function(){
  var $ = function(id){return document.getElementById(id)};
  var ZN = ['','중앙','신앙문 위','신앙문 아래','수행문 위','수행문 아래','네 귀퉁이'];
  var CIRC = ['','①','②','③','④','⑤','⑥','⑦','⑧','⑨'];
  var toks = Array.prototype.slice.call(document.querySelectorAll('.tk'));
  var ans=$('ans'), msg=$('msg'), where=$('where'), dots=$('dots'), score=$('score');

  function norm(s){ return String(s).normalize('NFC').replace(/[\s.,·]/g,''); }

  toks.forEach(function(el,i){
    el.dataset.id = i;
    el.dataset.t = el.dataset.a || el.textContent.trim();
    el.dataset.tx = el.textContent;
  });
  var byZone = {1:[],2:[],3:[],4:[],5:[],6:[]};
  toks.forEach(function(el){ byZone[el.dataset.z].push(+el.dataset.id); });
  function T(id){ return toks[id]; }
  function ansOf(id){ return T(id).dataset.t; }
  function len(id){ return norm(ansOf(id)).length; }
  function okList(id){
    var l=[norm(ansOf(id))]; var a=T(id).dataset.alt;
    if (a) a.split('|').forEach(function(x){l.push(norm(x))});
    return l;
  }

  var state = {zones:[], pick:{}, status:{}, tries:{}, active:null};

  var sched=[];
  function nextCorner(){
    if(!sched.length){
      sched=[1,1,0,0,0];
      for (var i=sched.length-1;i>0;i--){ var j=Math.floor(Math.random()*(i+1)); var t=sched[i]; sched[i]=sched[j]; sched[j]=t; }
    }
    return sched.pop();
  }
  function newRound(){
    state.pick={}; state.status={}; state.tries={};
    var zs=[1,2,3,4,5];
    if (nextCorner()) zs[Math.floor(Math.random()*5)]=6;
    for (var i=zs.length-1;i>0;i--){ var j=Math.floor(Math.random()*(i+1)); var t=zs[i]; zs[i]=zs[j]; zs[j]=t; }
    state.zones=zs.slice(0,5).sort(function(a,b){return a-b});
    state.zones.forEach(function(z){
      var list=byZone[z]; state.pick[z]=list[Math.floor(Math.random()*list.length)];
      state.status[z]='open'; state.tries[z]=0;
    });
    state.active=state.zones[0];
    $('result').hidden=true; ans.value=''; setMsg(''); paint();
  }
  function setMsg(t,c){ msg.textContent=t||''; msg.className='msg'+(c?' '+c:''); }

  function paint(){
    toks.forEach(function(el){
      var id=+el.dataset.id, z=+el.dataset.z;
      el.textContent='';
      if (state.pick[z]!==id){ el.textContent=el.dataset.tx; return; }
      var st=state.status[z], o=el.dataset.o, L=len(id)*1.1+.9;
      var b=document.createElement('button');
      b.type='button'; b.dataset.z=z;
      b.className='blank '+o+(st==='open'?'':' '+st)+(state.active===z&&st==='open'?' active':'');
      if (o==='v') b.style.height=L+'em'; else b.style.minWidth=L+'em';
      b.textContent = st==='open' ? CIRC[z] : ansOf(id);
      b.setAttribute('aria-label','구간 '+z+' 빈칸'+(st==='open'?'':', '+ansOf(id)));
      el.appendChild(b);
    });
    dots.innerHTML='';
    state.zones.forEach(function(z){
      var d=document.createElement('span'), st=state.status[z];
      d.className='dot '+(st==='open'?'':st)+(state.active===z&&st==='open'?' now':'');
      d.textContent = st==='ok'?'✓':CIRC[z];
      dots.appendChild(d);
    });
    var ok=countOk();
    score.textContent='정답 '+ok+' / 5';
    var a=state.active;
    if (a && state.status[a]==='open'){
      var id=state.pick[a];
      where.innerHTML='<b>구간 '+CIRC[a]+' '+ZN[a]+'</b> · '+len(id)+'글자<br>'+T(id).dataset.h;
    } else if (allDone()) where.textContent='모든 구간을 풀었습니다';
    else where.textContent='빈칸을 눌러 시작하세요';
  }
  function countOk(){ return state.zones.filter(function(z){return state.status[z]==='ok'}).length; }
  function allDone(){ return state.zones.every(function(z){return state.status[z]!=='open'}); }
  function nextOpen(from){
    var zs=state.zones, i=zs.indexOf(from);
    for (var k=1;k<=zs.length;k++){ var z=zs[(i+k)%zs.length]; if(state.status[z]==='open') return z; }
    return null;
  }
  function resolved(z){
    var nx=nextOpen(z); state.active=nx; ans.value=''; paint();
    if (nx) ans.focus(); else finish();
  }
  function finish(){
    ans.blur();
    var ok=countOk();
    $('rtitle').textContent = ok===5 ? '5문제 모두 맞혔습니다' : '5문제 중 '+ok+'개 맞혔습니다';
    $('rtext').textContent = ok===5 ? '교리도를 구간마다 정확히 기억하고 있습니다.' : '정답을 본 칸은 주황색입니다. 다시 풀어 보세요.';
    $('result').hidden=false; $('result').scrollIntoView({block:'nearest',behavior:'smooth'});
    setMsg('');
  }
  function flash(z){
    var b=document.querySelector('.blank[data-z="'+z+'"]'); if(!b) return;
    b.classList.add('shake'); setTimeout(function(){b.classList.remove('shake')},400);
  }

  $('board').addEventListener('click',function(e){
    var b=e.target.closest?e.target.closest('.blank'):null; if(!b) return;
    var z=+b.dataset.z; if(state.status[z]!=='open') return;
    state.active=z; ans.value=''; setMsg(''); paint(); ans.focus();
    setTimeout(function(){
      var nb=document.querySelector('.blank[data-z="'+z+'"]');
      if(nb&&nb.scrollIntoView) nb.scrollIntoView({block:'center',behavior:'smooth'});
    },260);
  });

  $('form').addEventListener('submit',function(e){
    e.preventDefault();
    var z=state.active;
    if(!z||state.status[z]!=='open'){ setMsg('먼저 분홍색 빈칸을 눌러 주세요.','bad'); return; }
    var v=norm(ans.value);
    if(!v){ setMsg('글자를 입력해 주세요.','bad'); return; }
    var id=state.pick[z];
    if(okList(id).indexOf(v)>-1){
      state.status[z]='ok'; setMsg('정답입니다: '+ansOf(id),'good'); resolved(z);
    } else {
      state.tries[z]++; flash(z);
      var extra=state.tries[z]>=2?' 첫 글자는 “'+ansOf(id).charAt(0)+'”입니다.':'';
      setMsg('틀렸습니다. '+len(id)+'글자입니다.'+extra,'bad'); ans.select();
    }
  });
  $('show').addEventListener('click',function(){
    var z=state.active;
    if(!z||state.status[z]!=='open'){ setMsg('먼저 분홍색 빈칸을 눌러 주세요.','bad'); return; }
    state.status[z]='shown'; setMsg('정답: '+ansOf(state.pick[z])); resolved(z);
  });
  $('again').addEventListener('click',function(){ newRound(); window.scrollTo({top:0,behavior:'smooth'}); });
  $('reset').addEventListener('click',newRound);

  newRound();
})();
</script>

</body>
</html>
