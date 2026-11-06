<!DOCTYPE html><html lang="ar" dir="rtl"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover,user-scalable=no">
<title>هيمنة الفريق – TEAM DOMINANCE</title>
<style>
:root{color-scheme:dark;--bg:#0c0f12;--fg:#e8ecef;--gold:#f2b705;--blue:#2e7bd6;--red:#d6432e;--panel:rgba(10,14,18,.78);box-sizing:border-box}
*{box-sizing:border-box;-webkit-user-select:none;user-select:none;-webkit-tap-highlight-color:transparent}
html,body{margin:0;height:100%;overflow:hidden;background:var(--bg);color:var(--fg);font-family:system-ui,"Segoe UI",Tahoma,sans-serif;touch-action:none}
canvas#c{position:fixed;inset:0;width:100%;height:100%}
.ov{position:fixed;inset:0;display:flex;align-items:center;justify-content:center;flex-direction:column;gap:10px;background:radial-gradient(ellipse at 50% 30%,#1d2a34,#080a0c);z-index:20;text-align:center;padding:12px}
h1{margin:0;font-size:clamp(26px,6vw,46px);letter-spacing:2px;color:var(--gold)}h1 small{display:block;font-size:.4em;color:var(--fg);letter-spacing:6px}
.row{display:flex;gap:10px;flex-wrap:wrap;justify-content:center;align-items:center;font-size:14px}
select,input[type=range],.in{background:#1b242c;color:var(--fg);border:1px solid #3a4a56;border-radius:8px;padding:8px;font-size:14px}
.go{background:var(--gold);color:#111;border:0;border-radius:10px;padding:14px 38px;font-size:20px;font-weight:800}
.stat{font-size:12px;opacity:.75}
#hud{position:fixed;inset:0;z-index:5;pointer-events:none;display:none}
#top{position:absolute;top:env(safe-area-inset-top,0px);left:50%;transform:translateX(-50%);display:flex;gap:10px;align-items:center;background:var(--panel);padding:4px 14px;border-radius:0 0 12px 12px;font-weight:800;font-size:18px}
#sb{color:var(--blue)}#sr{color:var(--red)}#tm{font-size:15px;color:var(--gold);min-width:52px;text-align:center}
#mm{position:absolute;top:calc(env(safe-area-inset-top,0px) + 6px);left:8px;background:var(--panel);border-radius:8px;border:1px solid #3a4a56}
#xh{position:absolute;left:50%;top:50%;width:18px;height:18px;margin:-9px;border:2px solid #fff8;border-radius:50%}
#xh.hit{border-color:#f33;transform:scale(1.4)}
#ammo{position:absolute;right:calc(env(safe-area-inset-right,0px) + 150px);bottom:calc(env(safe-area-inset-bottom,0px) + 10px);background:var(--panel);padding:6px 12px;border-radius:10px;text-align:center}
#ammo b{font-size:26px}#hpw{position:absolute;left:50%;transform:translateX(-50%);bottom:calc(env(safe-area-inset-bottom,0px) + 8px);width:200px;height:12px;background:#0009;border-radius:6px;overflow:hidden}
#hp{height:100%;width:100%;background:#4cd964}
#fl{position:absolute;inset:0;background:radial-gradient(transparent 40%,#d00);opacity:0;transition:opacity .25s}
#touch{position:fixed;inset:0;z-index:4;display:none}
.btn{position:absolute;pointer-events:auto;border-radius:50%;background:#1b242ccc;border:2px solid #fff6;color:#fff;font-size:13px;font-weight:700;display:flex;align-items:center;justify-content:center;text-align:center}
.btn:active,.btn.on{background:var(--gold);color:#111}
#bf{width:84px;height:84px;right:calc(env(safe-area-inset-right,0px) + 26px);bottom:calc(env(safe-area-inset-bottom,0px) + 40px);font-size:16px}
#bj{width:60px;height:60px;right:130px;bottom:calc(env(safe-area-inset-bottom,0px) + 22px)}
#br{width:54px;height:54px;right:22px;bottom:calc(env(safe-area-inset-bottom,0px) + 140px)}
#bw{width:54px;height:54px;right:86px;bottom:calc(env(safe-area-inset-bottom,0px) + 120px)}
#ba{width:54px;height:54px;right:150px;bottom:calc(env(safe-area-inset-bottom,0px) + 100px)}
#js{position:absolute;width:120px;height:120px;border-radius:50%;border:2px solid #fff5;background:#fff1;display:none}
#kn{position:absolute;width:50px;height:50px;border-radius:50%;background:#fffa;left:35px;top:35px}
</style></head><body>
<canvas id="c"></canvas>
<div id="hud"><div id="top"><span id="sb">0</span><span id="tm">10:00</span><span id="sr">0</span></div>
<canvas id="mm" width="110" height="76"></canvas><div id="xh"></div><div id="fl"></div>
<div id="hpw"><div id="hp"></div></div><div id="ammo"><div id="wn" class="stat"></div><b id="am">30</b> / <span id="rs">120</span></div></div>
<div id="touch"><div id="js"><div id="kn"></div></div>
<div class="btn" id="bf">🔥 نار</div><div class="btn" id="bj">قفز</div><div class="btn" id="br">تلقيم</div><div class="btn" id="bw">سلاح</div><div class="btn" id="ba">تصويب</div></div>
<div class="ov" id="menu"><h1>هيمنة الفريق<small>TEAM DOMINANCE</small></h1>
<div class="stat" id="st"></div>
<div class="row"><label>الصعوبة <select id="df"><option value="0">سهل</option><option value="1">متوسط</option><option value="2">قوي</option><option value="3">محترف</option></select></label>
<label>الرسومات <select id="ql"><option value="0">منخفض</option><option value="1">عالي</option></select></label>
<label>الحساسية <input type="range" id="sn" min="0.3" max="2.5" step="0.1"></label></div>
<button class="go" id="go">ابدأ التدريب – 4 ضد 4</button>
<div class="row"><input class="in" id="mn" placeholder="اسمك" maxlength="12" style="width:100px"><input class="in" id="ma" placeholder="192.168.x.x:8080" style="width:170px" dir="ltr"><select id="mt"><option value="b">الأزرق</option><option value="r">الأحمر</option></select><button class="go" id="mj" style="font-size:15px;padding:10px 20px">لعب Wi-Fi</button></div>
<div class="stat">المستودع • 10 دقائق • الفائز أول من يصل 40 قتلة<br>جوال: عصا يسار، اسحب يمين للتدوير • حاسوب: WASD + ماوس + نقر</div></div>
<div class="ov" id="end" style="display:none"><h1 id="et"></h1><div id="es" class="row"></div><button class="go" onclick="location.reload()">القائمة</button></div>
<div class="ov" id="lob" style="display:none"><h1 style="font-size:28px">غرفة Wi-Fi</h1><div id="lp" style="min-width:260px;font-size:16px;line-height:1.8"></div><div class="stat" id="ls"></div><div class="row"><button class="go" id="lr" style="font-size:16px;padding:10px 24px">جاهز</button><button class="go" id="lst" style="font-size:16px;padding:10px 24px;display:none">ابدأ المباراة</button></div></div>
<div class="ov" id="pz" style="display:none;background:#000a"><h1>إيقاف مؤقت</h1><button class="go" id="rs2">متابعة</button></div>
<script src="three.min.js"></script>
<script>window.THREE||document.write('<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"><\/script>')</script>
<script>
(()=>{
const $=id=>document.getElementById(id),T=THREE,R=.4,HW=30,HD=20;
let S={sens:1,diff:1,q:1,k:0,d:0,m:0,w:0};
try{Object.assign(S,JSON.parse(localStorage.getItem('td')||'{}'))}catch(e){}
const save=()=>{try{localStorage.setItem('td',JSON.stringify(S))}catch(e){}};
const showSt=()=>$('st').textContent=`مباريات ${S.m} • انتصارات ${S.w} • قتلات ${S.k} • وفيات ${S.d}`;
showSt();$('df').value=S.diff;$('ql').value=S.q;$('sn').value=S.sens;
$('df').onchange=e=>{S.diff=+e.target.value;save()};$('ql').onchange=e=>{S.q=+e.target.value;save()};$('sn').oninput=e=>{S.sens=+e.target.value;save()};
if(typeof THREE==='undefined'){$('go').disabled=true;$('go').textContent='تعذر تحميل Three.js (يلزم اتصال مرة واحدة)'}
const WP=[{n:'AR-47',dmg:26,rate:.1,mag:30,res:150,sp:.012,kick:.012,f:200},{n:'SMG-9',dmg:17,rate:.065,mag:40,res:200,sp:.02,kick:.008,f:300},{n:'SNP-24',dmg:90,rate:1,mag:5,res:25,sp:.002,kick:.04,f:110}];
const DP=[{sp:.09,rate:.45,rx:.9,spd:3},{sp:.05,rate:.3,rx:.6,spd:3.8},{sp:.03,rate:.2,rx:.35,spd:4.5},{sp:.015,rate:.12,rx:.15,spd:5.2}];
let MP={on:false,ws:null,id:0,team:'b'},RP={},ren,scene,cam,B=[],E=[],pe,gun,flash,sc={b:0,r:0},tleft=600,playing=false,paused=false,over=false,ot=false;
let yaw=0,pitch=0,vy=0,fire=false,aim=false,wi=0,mv={id:null,x:0,y:0,sx:0,sy:0},lk={id:null,x:0,y:0},keys={},ammo=[],rl=0,cd=0,kick=0,regen=0;
const clamp=(v,a,b)=>Math.max(a,Math.min(b,v)),rnd=(a,b)=>a+Math.random()*(b-a);
function box(x,z,w,d,h,col,y0){const b={x0:x-w/2,x1:x+w/2,z0:z-d/2,z1:z+d/2,h:h};B.push(b);
 const m=new T.Mesh(new T.BoxGeometry(w,h,d),new T.MeshStandardMaterial({color:col,roughness:.7,metalness:col>0x555555&&col<0x999999?.1:.4}));
 m.position.set(x,h/2,z);m.castShadow=m.receiveShadow=true;scene.add(m)}
function build(){
 scene=new T.Scene();scene.background=new T.Color(0x14181c);scene.fog=new T.Fog(0x14181c,25,S.q?90:50);
 cam=new T.PerspectiveCamera(75,innerWidth/innerHeight,.05,120);cam.rotation.order='YXZ';scene.add(cam);
 ren=new T.WebGLRenderer({canvas:$('c'),antialias:!!S.q});ren.setPixelRatio(S.q?Math.min(devicePixelRatio,2):1);ren.setSize(innerWidth,innerHeight);
 ren.shadowMap.enabled=!!S.q;
 const cv=document.createElement('canvas');cv.width=cv.height=128;const g=cv.getContext('2d');g.fillStyle='#6b6b68';g.fillRect(0,0,128,128);
 for(let i=0;i<700;i++){g.fillStyle=Math.random()<.5?'rgba(0,0,0,.09)':'rgba(255,255,255,.05)';g.fillRect(Math.random()*128,Math.random()*128,rnd(1,6),rnd(1,6))}
 const tx=new T.CanvasTexture(cv);tx.wrapS=tx.wrapT=T.RepeatWrapping;tx.repeat.set(14,9);
 const fl=new T.Mesh(new T.PlaneGeometry(HW*2,HD*2),new T.MeshStandardMaterial({map:tx,roughness:.9}));fl.rotation.x=-Math.PI/2;fl.receiveShadow=true;scene.add(fl);
 for(const[s,c]of[[-1,0x1f4f9a],[1,0x9a2f1f]]){const p=new T.Mesh(new T.PlaneGeometry(8,HD*2),new T.MeshBasicMaterial({color:c,transparent:true,opacity:.35}));p.rotation.x=-Math.PI/2;p.position.set(s*26,.01,0);scene.add(p)}
 const wm=new T.MeshStandardMaterial({color:0x4a5258,roughness:.6,metalness:.5,side:T.DoubleSide});
 for(const[x,z,w,d]of[[0,-HD,HW*2,.4],[0,HD,HW*2,.4],[-HW,0,.4,HD*2],[HW,0,.4,HD*2]]){const m=new T.Mesh(new T.BoxGeometry(w,12,d),wm);m.position.set(x,6,z);scene.add(m)}
 const ce=new T.Mesh(new T.PlaneGeometry(HW*2,HD*2),new T.MeshStandardMaterial({color:0x2a3036,side:T.DoubleSide}));ce.rotation.x=Math.PI/2;ce.position.y=12;scene.add(ce);
 for(let x=-24;x<=24;x+=8){const bm=new T.Mesh(new T.BoxGeometry(.5,.6,HD*2),new T.MeshStandardMaterial({color:0x3a4046,metalness:.6}));bm.position.set(x,11.6,0);scene.add(bm)}
 scene.add(new T.HemisphereLight(0xbfd0e0,0x333333,.55));
 const sun=new T.DirectionalLight(0xffffff,.55);sun.position.set(10,30,8);sun.castShadow=!!S.q;sun.shadow.mapSize.set(1024,1024);
 const sc2=sun.shadow.camera;sc2.left=-35;sc2.right=35;sc2.top=25;sc2.bottom=-25;sc2.far=60;scene.add(sun);
 for(let x=-24;x<=24;x+=12)for(const z of[-10,10]){const l=new T.PointLight(0xffe2b0,.5,28);l.position.set(x,10.5,z);scene.add(l);
  const lm=new T.Mesh(new T.BoxGeometry(2,.2,.6),new T.MeshBasicMaterial({color:0xfff2cc}));lm.position.set(x,11.8,z);scene.add(lm)}
 const BL=0x2b5fa8,RD=0xa83a2b,GY=0x777b7e,CN=0x8a8a80,CR=0x4a5a3a;
 [[0,0,6,2.5,2.6,BL],[0,-8,2.5,6,2.6,RD],[0,8,2.5,6,2.6,GY],[-9,-4,6,2.5,2.6,RD],[9,4,6,2.5,2.6,BL],[-9,6,2.5,5,2.6,BL],[9,-6,2.5,5,2.6,RD],
 [-17,0,2,8,1.2,CN],[17,0,2,8,1.2,CN],[-14,-12,5,2.5,2.6,GY],[14,12,5,2.5,2.6,GY],[-14,12,4,1.2,1.2,CN],[14,-12,4,1.2,1.2,CN],
 [-5,-14,1.2,4,1.2,CN],[5,14,1.2,4,1.2,CN],[-21,-8,3,3,1.5,CR],[21,8,3,3,1.5,CR],[-21,9,3,3,1.5,CR],[21,-9,3,3,1.5,CR],[4,-3,3,3,1.5,CR],[-4,3,3,3,1.5,CR]].forEach(a=>box(...a));
 gun=new T.Group();const gm=new T.MeshStandardMaterial({color:0x222426,metalness:.6,roughness:.4});
 const p1=new T.Mesh(new T.BoxGeometry(.07,.11,.55),gm);p1.position.set(0,0,0);const p2=new T.Mesh(new T.BoxGeometry(.05,.05,.3),gm);p2.position.set(0,.02,-.4);
 const p3=new T.Mesh(new T.BoxGeometry(.05,.16,.07),gm);p3.position.set(0,-.12,-.05);gun.add(p1,p2,p3);
 flash=new T.Mesh(new T.BoxGeometry(.1,.1,.1),new T.MeshBasicMaterial({color:0xffcc55}));flash.position.set(0,.02,-.6);flash.visible=false;gun.add(flash);
 gun.position.set(.2,-.2,-.45);cam.add(gun);
 pe={team:'b',x:-26,y:0,z:0,hp:100,alive:true,isP:true,k:0,d:0,rs:0};E.push(pe);
 if(!MP.on){for(let i=0;i<3;i++)mkBot('b');for(let i=0;i<4;i++)mkBot('r');E.forEach(spawn)}else{pe.team=MP.team;spawn(pe)}
 addEventListener('resize',()=>{cam.aspect=innerWidth/innerHeight;cam.updateProjectionMatrix();ren.setSize(innerWidth,innerHeight)});
}
function mkBot(t){const c=t=='b'?0x2e6fd6:0xd6432e,m=new T.MeshStandardMaterial({color:c,roughness:.7}),k=new T.MeshStandardMaterial({color:0x2c3126}),g=new T.Group();
 const add=(geo,mat,x,y,z)=>{const q=new T.Mesh(geo,mat);q.position.set(x,y,z);q.castShadow=true;g.add(q)};
 add(new T.BoxGeometry(.5,.7,.3),m,0,1.15,0);add(new T.BoxGeometry(.2,.75,.22),k,-.13,.38,0);add(new T.BoxGeometry(.2,.75,.22),k,.13,.38,0);
 add(new T.SphereGeometry(.17,10,8),new T.MeshStandardMaterial({color:0xd8b090}),0,1.65,0);add(new T.BoxGeometry(.38,.14,.38),k,0,1.8,0);
 add(new T.BoxGeometry(.06,.08,.6),new T.MeshStandardMaterial({color:0x111}),.28,1.2,.3);scene.add(g);
 const n={team:t,x:0,y:0,z:0,hp:100,alive:true,mesh:g,k:0,d:0,rs:0,cd:0,rl:0,mag:30,seen:0,sd:1,st:0,wt:0,wa:0,lx:0,lz:0,lt:0};if(!MP.on)E.push(n);return n}
function spawn(e){e.x=(e.team=='b'?-1:1)*rnd(25,28);e.z=rnd(-15,15);e.y=0;e.hp=100;e.alive=true;e.mag=30;if(e.mesh)e.mesh.visible=true;
 if(e.isP){yaw=e.team=='b'?-Math.PI/2:Math.PI/2;pitch=0;vy=0;ammo=WP.map(w=>({m:w.mag,r:w.res}));rl=0;hud();$('ov-d')&&0}}
function col(e){let g=0;for(const b of B)if(e.x>b.x0-R&&e.x<b.x1+R&&e.z>b.z0-R&&e.z<b.z1+R){
 if(e.y>=b.h-.35)g=Math.max(g,b.h);else{const l=e.x-(b.x0-R),r=b.x1+R-e.x,d=e.z-(b.z0-R),u=b.z1+R-e.z,m=Math.min(l,r,d,u);
 if(m==l)e.x=b.x0-R;else if(m==r)e.x=b.x1+R;else if(m==d)e.z=b.z0-R;else e.z=b.z1+R}}
 e.x=clamp(e.x,-HW+R,HW-R);e.z=clamp(e.z,-HD+R,HD-R);return g}
function rayBox(o,d,x0,x1,y0,y1,z0,z1){let tn=0,tf=1e9;const L=[x0,y0,z0],H=[x1,y1,z1];
 for(let i=0;i<3;i++){if(Math.abs(d[i])<1e-8){if(o[i]<L[i]||o[i]>H[i])return 1e9}else{let a=(L[i]-o[i])/d[i],b=(H[i]-o[i])/d[i];if(a>b){const t=a;a=b;b=t}tn=Math.max(tn,a);tf=Math.min(tf,b);if(tn>tf)return 1e9}}return tn}
function blocked(o,d,dist){for(const b of B)if(rayBox(o,d,b.x0,b.x1,0,b.h,b.z0,b.z1)<dist)return true;return false}
function shoot(o,d,sh,dmg){let bt=90,hit=null;for(const b of B){const t=rayBox(o,d,b.x0,b.x1,0,b.h,b.z0,b.z1);if(t<bt)bt=t}
 for(const e of E)if(e.alive&&e.team!=sh.team){const t=rayBox(o,d,e.x-.35,e.x+.35,e.y,e.y+1.85,e.z-.35,e.z+.35);if(t<bt){bt=t;hit=e}}
 if(hit){const py=o[1]+d[1]*bt;hurt(hit,py>hit.y+1.5?dmg*2:dmg,sh)}}
function hurt(e,dm,sh){if(!e.alive||over)return;e.hp-=dm;
 if(e.isP){$('fl').style.opacity=1;setTimeout(()=>$('fl').style.opacity=0,200);regen=5}
 if(sh.isP){$('xh').className='hit';setTimeout(()=>$('xh').className='',120)}
 if(e.hp<=0){e.alive=false;e.rs=3;e.d++;sh.k++;sc[sh.team]++;if(e.mesh)e.mesh.visible=false;if(e.isP){fire=false}hud();
 if(sc.b>=40||sc.r>=40||(ot&&sc.b!=sc.r))finish()}}
function snd(f,l,v){try{ac=window.ac||(window.ac=new AudioContext());const o=ac.createOscillator(),g=ac.createGain();o.type='sawtooth';o.frequency.value=f;g.gain.setValueAtTime(v||.1,ac.currentTime);g.gain.exponentialRampToValueAtTime(.001,ac.currentTime+l);o.connect(g);g.connect(ac.destination);o.start();o.stop(ac.currentTime+l)}catch(e){}}
function hud(){$('sb').textContent=sc.b;$('sr').textContent=sc.r;const a=ammo[wi];if(a){$('am').textContent=rl>0?'…':a.m;$('rs').textContent=a.r;$('wn').textContent=WP[wi].n}
 $('hp').style.width=Math.max(0,pe.hp)+'%'}
function finish(){if(over)return;over=true;playing=false;const w=sc.b>sc.r;S.m++;if(w)S.w++;S.k+=pe.k;S.d+=pe.d;save();
 $('hud').style.display=$('touch').style.display='none';$('end').style.display='flex';$('et').textContent=w?'🏆 فوز':'💀 خسارة';
 $('es').innerHTML=`<span>الأزرق ${sc.b}</span><span>الأحمر ${sc.r}</span><span>قتلاتك ${pe.k}</span><span>وفياتك ${pe.d}</span>`}
function reload(){const a=ammo[wi],w=WP[wi];if(rl>0||a.m==w.mag||a.r<=0)return;rl=1.6;snd(180,.2,.05)}
function fireP(){const w=WP[wi],a=ammo[wi];if(cd>0||rl>0||!pe.alive)return;if(a.m<=0){reload();return}
 cd=w.rate;a.m--;kick=1;const sp=w.sp*(aim?.35:1),d=new T.Vector3();cam.getWorldDirection(d);d.x+=rnd(-sp,sp);d.y+=rnd(-sp,sp);d.z+=rnd(-sp,sp);d.normalize();
 if(MP.on)msg({t:'fire',d:[d.x,d.y,d.z],w:wi});else shoot([pe.x,pe.y+1.6,pe.z],[d.x,d.y,d.z],pe,w.dmg);pitch=clamp(pitch+w.kick*(aim?.5:1),-1.4,1.4);snd(w.f,.09,.12);flash.visible=true;setTimeout(()=>flash.visible=false,40);hud()}
function bot(b,dt){if(!b.alive){b.rs-=dt;if(b.rs<=0)spawn(b);return}
 let tg=null,bd=1e9;for(const e of E)if(e.alive&&e.team!=b.team){const d=Math.hypot(e.x-b.x,e.z-b.z);if(d<bd){bd=d;tg=e}}
 if(!tg)return;const D=DP[S.diff],o=[b.x,1.5,b.z],dx=tg.x-b.x,dy=tg.y+1.4-1.5,dz=tg.z-b.z,dist=Math.hypot(dx,dy,dz),dir=[dx/dist,dy/dist,dz/dist];
 b.cd-=dt;if(b.rl>0){b.rl-=dt;if(b.rl<=0)b.mag=30}
 let mx=0,mz=0,sp=D.spd;const vis=dist<45&&!blocked(o,dir,dist);
 b.mesh.rotation.y=Math.atan2(dx,dz);
 if(vis){b.seen+=dt;b.st-=dt;if(b.st<=0){b.sd=-b.sd;b.st=rnd(.8,1.8)}
  const px=-dz/dist,pz=dx/dist;mx=px*b.sd*.6;mz=pz*b.sd*.6;if(dist>18){mx+=dx/dist;mz+=dz/dist}else if(dist<7){mx-=dx/dist;mz-=dz/dist}
  if(b.seen>D.rx&&b.cd<=0&&b.rl<=0){if(b.mag<=0){b.rl=2}else{b.mag--;b.cd=D.rate;const s=D.sp*(1+dist/25),d2=[dir[0]+rnd(-s,s),dir[1]+rnd(-s,s),dir[2]+rnd(-s,s)];shoot(o,d2,b,14)}}}
 else{b.seen=0;if(b.wt>0){b.wt-=dt;mx=Math.cos(b.wa);mz=Math.sin(b.wa)}else{mx=dx/dist;mz=dz/dist}}
 b.lt+=dt;if(b.lt>.6){if(!vis&&Math.hypot(b.x-b.lx,b.z-b.lz)<.4){b.wt=1.2;b.wa=rnd(0,6.28)}b.lx=b.x;b.lz=b.z;b.lt=0}
 const m=Math.hypot(mx,mz)||1;b.x+=mx/m*sp*dt*(vis?.7:1);b.z+=mz/m*sp*dt*(vis?.7:1);col(b);b.mesh.position.set(b.x,0,b.z)}
function upd(dt){
 if(!pe.alive){if(!MP.on){pe.rs-=dt;if(pe.rs<=0){spawn(pe);$('fl').style.opacity=0}}}
 else{let jx=mv.x,jy=mv.y;if(keys.KeyW)jy-=1;if(keys.KeyS)jy+=1;if(keys.KeyA)jx-=1;if(keys.KeyD)jx+=1;
  const m=Math.hypot(jx,jy),run=m>.92||keys.ShiftLeft,sp=(run?7.5:5)*(aim?.6:1);if(m>1){jx/=m;jy/=m}
  const s=Math.sin(yaw),c=Math.cos(yaw);pe.x+=(jx*c+jy*s)*sp*dt;pe.z+=(-jx*s+jy*c)*sp*dt;
  vy-=18*dt;pe.y+=vy*dt;const g=col(pe);if(pe.y<=g){pe.y=g;vy=0;pe.on=true}else pe.on=false;
  if(pe.hp<100&&!MP.on){regen-=dt;if(regen<=0)pe.hp=Math.min(100,pe.hp+12*dt)}
  if(fire)fireP();if(rl>0){rl-=dt;if(rl<=0){const a=ammo[wi],w=WP[wi],n=Math.min(w.mag-a.m,a.r);a.m+=n;a.r-=n;hud()}}}
 cd-=dt;kick=Math.max(0,kick-dt*8);
 if(MP.on)mpStep(dt);else for(const e of E)if(!e.isP)bot(e,dt);
 cam.position.set(pe.x,pe.y+1.6,pe.z);cam.rotation.set(pitch,yaw,0);cam.fov+=((aim?(wi==2?25:50):75)-cam.fov)*.25;cam.updateProjectionMatrix();
 gun.position.set(aim?0:.2,aim?-.1:-.2,-.45+kick*.05);gun.rotation.x=kick*.05;
 if(!ot&&!MP.on){tleft-=dt;if(tleft<=0){tleft=0;if(sc.b==sc.r){ot=true}else finish()}}
 const t=Math.ceil(tleft);$('tm').textContent=ot?'إضافي':Math.floor(t/60)+':'+String(t%60).padStart(2,'0');
 $('hp').style.width=Math.max(0,pe.hp)+'%';
}
const mc=$('mm').getContext('2d');let mt=0;
function mini(dt){mt+=dt;if(mt<.1)return;mt=0;mc.clearRect(0,0,110,76);const k=110/60,X=x=>(x+HW)*k,Z=z=>(z+HD)*k;
 mc.fillStyle='#8a8f94';for(const b of B)mc.fillRect(X(b.x0),Z(b.z0),(b.x1-b.x0)*k,(b.z1-b.z0)*k);
 for(const e of E.concat(Object.values(RP)))if(e.alive&&(!MP.on||e.isP||e.team==pe.team)){mc.fillStyle=e.isP?'#fff':e.team=='b'?'#2e7bd6':'#d6432e';mc.beginPath();mc.arc(X(e.x),Z(e.z),e.isP?3.5:2.5,0,7);mc.fill()}}
let last=0;function loop(t){requestAnimationFrame(loop);if(!playing||paused){last=t;return}const dt=Math.min(.05,(t-last)/1000||.016);last=t;upd(dt);mini(dt);ren.render(scene,cam)}
function start(){build();playing=true;$('menu').style.display='none';$('hud').style.display='block';$('touch').style.display='block';
 try{document.documentElement.requestFullscreen().then(()=>screen.orientation.lock('landscape')).catch(()=>{})}catch(e){}
 try{navigator.wakeLock&&navigator.wakeLock.request('screen').catch(()=>{})}catch(e){}
 history.pushState(1,'');hud();requestAnimationFrame(loop)}
$('go').onclick=start;
addEventListener('popstate',()=>{if(playing){paused=true;$('pz').style.display='flex';history.pushState(1,'')}});
$('rs2').onclick=()=>{paused=false;$('pz').style.display='none'};
document.addEventListener('visibilitychange',()=>{if(document.hidden&&playing){paused=true;$('pz').style.display='flex'}});
// ===== Wi-Fi multiplayer =====
const msg=o=>{if(MP.ws&&MP.ws.readyState==1)MP.ws.send(JSON.stringify(o))};
let lob=null,mpT=0;
function lobUI(m){lob=m;const me=m.players.find(p=>p.id==m.you);
 $('lp').innerHTML=m.players.map(p=>`<div style="color:${p.team=='b'?'#6aa8ff':'#ff7b66'}">${p.id==m.host?'👑 ':''}${p.name} ${p.ready?'✅':'⏳'}</div>`).join('');
 $('lr').textContent=me&&me.ready?'إلغاء الجاهزية':'جاهز';$('lst').style.display=m.host==m.you?'':'none';$('ls').textContent='متصل • '+m.players.length+' لاعب'}
$('mj').onclick=()=>{const a=$('ma').value.trim()||(location.protocol=='http:'?location.host:'');if(!a){alert('اكتب عنوان الخادم مثل 192.168.1.5:8080');return}
 try{MP.ws=new WebSocket('ws://'+a)}catch(e){alert('تعذر الاتصال');return}
 MP.team=$('mt').value;const ws=MP.ws;
 ws.onopen=()=>{msg({t:'join',name:$('mn').value.trim()||'لاعب',team:MP.team});$('menu').style.display='none';$('lob').style.display='flex'};
 ws.onerror=()=>{if(!MP.on)alert('تعذر الاتصال بالخادم: تأكد من العنوان والشبكة. (الصفحة المنشورة على https لا تتصل؛ افتح اللعبة من الخادم)')};
 ws.onclose=()=>{if(MP.on&&!over){playing=false;$('hud').style.display=$('touch').style.display='none';$('end').style.display='flex';$('et').textContent='انقطع الاتصال';$('es').textContent=''}
  else if(!MP.on&&!over){$('lob').style.display='none';$('menu').style.display='flex'}};
 ws.onmessage=e=>onM(JSON.parse(e.data))};
$('lr').onclick=()=>{const me=lob&&lob.players.find(p=>p.id==lob.you);msg({t:'ready',v:!(me&&me.ready)})};
$('lst').onclick=()=>msg({t:'start'});
function onM(m){switch(m.t){
 case'welcome':MP.id=m.id;break;
 case'lobby':lobUI(m);break;
 case'err':alert(m.m);break;
 case'go':MP.on=true;sc={b:0,r:0};over=false;$('lob').style.display='none';start();break;
 case'respawn':if(!pe)break;pe.x=m.x;pe.z=m.z;pe.y=0;pe.hp=100;pe.alive=true;yaw=m.x<0?-Math.PI/2:Math.PI/2;pitch=0;vy=0;ammo=WP.map(w=>({m:w.mag,r:w.res}));rl=0;$('fl').style.opacity=0;hud();break;
 case'dmg':pe.hp=m.hp;$('fl').style.opacity=1;setTimeout(()=>$('fl').style.opacity=0,200);hud();break;
 case'hit':$('xh').className='hit';setTimeout(()=>$('xh').className='',120);break;
 case'death':pe.alive=false;fire=false;pe.hp=0;hud();break;
 case'snap':{if(!MP.on||!pe)break;sc=m.sc;tleft=m.tl;ot=m.ot;const seen={};
  for(const a of m.p){const[id,tm,x,y,z,yw,hp,al,k,d]=a;seen[id]=1;
   if(id==MP.id){pe.k=k;pe.d=d;if(al&&pe.alive)pe.hp=hp;continue}
   let r=RP[id];if(!r){r=RP[id]=mkBot(tm);r.mesh.position.set(x,y,z)}
   r.tx=x;r.ty=y;r.tz=z;r.yw=yw+Math.PI;r.x=x;r.z=z;r.team=tm;r.alive=!!al;r.mesh.visible=!!al}
  for(const id in RP)if(!seen[id]){scene.remove(RP[id].mesh);delete RP[id]}
  hud();break}
 case'end':over=true;playing=false;S.m++;if(m.win==pe.team)S.w++;S.k+=pe.k;S.d+=pe.d;save();
  $('hud').style.display=$('touch').style.display='none';$('end').style.display='flex';$('et').textContent=m.win=='x'?'تعادل':m.win==pe.team?'🏆 فوز':'💀 خسارة';
  $('es').innerHTML=`<span>الأزرق ${m.sc.b}</span><span>الأحمر ${m.sc.r}</span><span>قتلاتك ${pe.k}</span><span>وفياتك ${pe.d}</span>`;break}}
function mpStep(dt){mpT+=dt;if(mpT>=.05){mpT=0;msg({t:'st',x:pe.x,y:pe.y,z:pe.z,yaw})}
 for(const id in RP){const r=RP[id],p=r.mesh.position;p.x+=(r.tx-p.x)*.3;p.y+=(r.ty-p.y)*.3;p.z+=(r.tz-p.z)*.3;let da=r.yw-r.mesh.rotation.y;da=Math.atan2(Math.sin(da),Math.cos(da));r.mesh.rotation.y+=da*.3}}
// touch
const T0=$('touch'),js=$('js'),kn=$('kn');
T0.addEventListener('touchstart',e=>{e.preventDefault();for(const t of e.changedTouches){
 if(t.clientX<innerWidth*.45){if(mv.id==null){mv={id:t.identifier,sx:t.clientX,sy:t.clientY,x:0,y:0};js.style.display='block';js.style.left=(t.clientX-60)+'px';js.style.top=(t.clientY-60)+'px';kn.style.left=kn.style.top='35px'}}
 else if(lk.id==null)lk={id:t.identifier,x:t.clientX,y:t.clientY}}},{passive:false});
T0.addEventListener('touchmove',e=>{e.preventDefault();for(const t of e.changedTouches){
 if(t.identifier==mv.id){let dx=(t.clientX-mv.sx)/50,dy=(t.clientY-mv.sy)/50;const m=Math.hypot(dx,dy);if(m>1){dx/=m;dy/=m}mv.x=dx;mv.y=dy;kn.style.left=(35+dx*40)+'px';kn.style.top=(35+dy*40)+'px'}
 else if(t.identifier==lk.id){const f=.0045*S.sens*(aim?.5:1);yaw-=(t.clientX-lk.x)*f;pitch=clamp(pitch-(t.clientY-lk.y)*f,-1.4,1.4);lk.x=t.clientX;lk.y=t.clientY}}},{passive:false});
const endT=e=>{for(const t of e.changedTouches){if(t.identifier==mv.id){mv={id:null,x:0,y:0,sx:0,sy:0};js.style.display='none'}if(t.identifier==lk.id)lk={id:null,x:0,y:0}}};
T0.addEventListener('touchend',endT);T0.addEventListener('touchcancel',endT);
const hold=(id,on,off)=>{const b=$(id);b.addEventListener('touchstart',e=>{e.preventDefault();e.stopPropagation();b.classList.add('on');on()},{passive:false});
 const u=e=>{e.preventDefault();e.stopPropagation();b.classList.remove('on');off&&off()};b.addEventListener('touchend',u);b.addEventListener('touchcancel',u)};
hold('bf',()=>fire=true,()=>fire=false);hold('bj',()=>{if(pe.on)vy=7.5});hold('br',reload);
hold('bw',()=>{wi=(wi+1)%3;rl=0;aim=false;hud()});hold('ba',()=>{aim=!aim});
// desktop
addEventListener('keydown',e=>{keys[e.code]=1;if(e.code=='Space'&&pe&&pe.on)vy=7.5;if(e.code=='KeyR')reload();if(e.code=='KeyQ'){wi=(wi+1)%3;rl=0;hud()}});
addEventListener('keyup',e=>keys[e.code]=0);
let drag=false;addEventListener('mousedown',e=>{if(!playing)return;if(e.button==0){fire=true;drag=true}if(e.button==2)aim=!aim});
addEventListener('mouseup',()=>{fire=false;drag=false});addEventListener('contextmenu',e=>e.preventDefault());
addEventListener('mousemove',e=>{if(playing&&drag){yaw-=e.movementX*.003*S.sens;pitch=clamp(pitch-e.movementY*.003*S.sens,-1.4,1.4)}});
})();
</script></body></html>
