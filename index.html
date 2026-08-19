<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dashboard Agosto 2026 · AustraliaPRO</title>
<script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.1/dist/chart.umd.js"></script>
<script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-datalabels@2.2.0/dist/chartjs-plugin-datalabels.min.js"></script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&family=DM+Sans:wght@400;500;700&display=optional');
:root{
  --navy:#234283;--navy-dark:#1a3268;--cyan:#209ef5;--cream:#f0efe9;--cream2:#f7f6f1;
  --cream3:#ebeae5;--orange:#EA580C;--green:#3ecf8e;--white:#ffffff;--gray-text:#455266;--border:#e4e6ee;
}
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:'DM Sans',sans-serif;background:#f4f5f9;color:#1c2333;font-size:14px;min-height:100vh;}

.header{background:linear-gradient(120deg,#1a3268 0%,#234283 55%,#209ef5 100%);padding:22px 30px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:10px;}
.header-left h1{font-family:'Plus Jakarta Sans',sans-serif;font-size:20px;font-weight:800;color:#ffffff;letter-spacing:-0.3px;}
.header-left p{font-size:12px;color:rgba(255,255,255,0.75);margin-top:4px;}
.badge-cache{background:var(--cyan);color:#052b4a;font-size:11px;font-weight:700;padding:5px 12px;border-radius:20px;}

.section-label{font-size:11px;font-weight:700;color:#7686a1;letter-spacing:.9px;text-transform:uppercase;margin:30px 0 12px;display:flex;align-items:center;gap:10px;max-width:1240px;margin-left:auto;margin-right:auto;padding:0 24px;}
.section-label::after{content:'';flex:1;height:1px;background:linear-gradient(90deg,#d8dcec,transparent);}
.page{max-width:1240px;margin:0 auto;padding:6px 24px 44px;}

.kpi-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(165px,1fr));gap:12px;}
.kcard{background:var(--white);border-radius:14px;padding:18px;border:1px solid var(--border);position:relative;overflow:hidden;}
.kcard::before{content:'';position:absolute;top:0;left:0;right:0;height:4px;}
.kcard.k1::before{background:linear-gradient(90deg,#234283,#1a3268);}
.kcard.k2::before{background:linear-gradient(90deg,#209ef5,#5fc0fb);}
.kcard.k3::before{background:linear-gradient(90deg,#3ecf8e,#8de3b8);}
.kcard.k4::before{background:linear-gradient(90deg,#EA580C,#f4915e);}
.klabel{font-size:10px;font-weight:700;color:#8b9ab3;text-transform:uppercase;letter-spacing:.5px;margin-bottom:8px;}
.kval{font-family:'Plus Jakarta Sans',sans-serif;font-size:29px;font-weight:800;line-height:1;}
.k1 .kval{color:#234283;} .k2 .kval{color:#0d7fc9;} .k3 .kval{color:#22a46a;} .k4 .kval{color:#c1470b;}
.ksub{font-size:11px;color:#a3aec2;margin-top:7px;}

.charts-row{display:grid;grid-template-columns:1.25fr 1fr;gap:14px;}
@media(max-width:980px){.charts-row{grid-template-columns:1fr;}}
.charts-row-2{display:grid;grid-template-columns:1fr 1fr;gap:14px;}
@media(max-width:980px){.charts-row-2{grid-template-columns:1fr;}}
.ccard{background:var(--white);border-radius:14px;padding:20px;border:1px solid var(--border);}
.ctitle{font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;font-weight:800;color:var(--navy);margin-bottom:3px;}
.csub{font-size:11px;color:#a3aec2;margin-bottom:16px;}
.cwrap{position:relative;}

.insight-card{background:var(--cream2);border:1px solid #e2ded0;border-left:5px solid var(--cyan);border-radius:14px;padding:22px 24px;}
.insight-card .tag{display:inline-block;background:var(--cyan);color:#052b4a;font-size:10px;font-weight:800;letter-spacing:.5px;text-transform:uppercase;padding:4px 11px;border-radius:20px;margin-bottom:12px;}
.insight-card h3{font-family:'Plus Jakarta Sans',sans-serif;font-size:15px;font-weight:800;color:var(--navy);margin-bottom:10px;}
.insight-card p{font-size:13px;color:#455266;line-height:1.75;margin-bottom:10px;}
.insight-card p:last-child{margin-bottom:0;}
.insight-card strong{color:var(--navy);}
.insight-card .big{font-family:'Plus Jakarta Sans',sans-serif;font-weight:800;color:#0d7fc9;}
.insight-card .note{font-size:12px;color:#5c6a52;background:#ffffff;border-radius:8px;padding:11px 14px;border:1px solid #e2ded0;}

.table-card{background:var(--white);border-radius:14px;border:1px solid var(--border);overflow:hidden;}
.table-scroll{overflow-x:auto;}
table{width:100%;border-collapse:collapse;font-size:12px;}
thead th{background:var(--navy);color:var(--white);padding:12px;text-align:left;font-family:'Plus Jakarta Sans',sans-serif;font-weight:700;font-size:11px;white-space:nowrap;}
thead th.hi{background:linear-gradient(135deg,#209ef5,#0d7fc9);}
tbody tr:nth-child(even){background:#f9fafc;}
tbody tr:hover{background:#eaf4fd;}
tbody td{padding:11px 12px;text-align:left;color:var(--gray-text);border-bottom:1px solid #eef1f7;white-space:nowrap;vertical-align:middle;}
tbody td.wrap{white-space:normal;line-height:1.45;max-width:230px;min-width:170px;}
tbody td.num{text-align:right;font-variant-numeric:tabular-nums;}
tbody td.muted{color:#b7c0d1;}

.pill{display:inline-block;font-size:10px;font-weight:700;padding:4px 11px;border-radius:20px;white-space:nowrap;}
.p-noelegible{background:#fde3d9;color:#a1451b;}
.p-noasistio{background:#fff0cd;color:#a06a00;}
.p-consultoria{background:linear-gradient(135deg,#3ecf8e,#22a46a);color:#ffffff;}
.p-completed{background:#d6f5e6;color:#17784f;}

.note-card{background:var(--white);border-radius:14px;border:1px solid var(--border);border-left:5px solid var(--orange);padding:24px 26px;}
.note-title{font-family:'Plus Jakarta Sans',sans-serif;font-size:16px;font-weight:800;color:var(--navy);margin-bottom:7px;}
.note-intro{font-size:13px;color:#556277;line-height:1.75;margin-bottom:18px;}
.note-card ul{padding-left:20px;}
.note-card li{font-size:13px;color:#556277;line-height:1.75;margin-bottom:8px;}
.note-card li::marker{color:var(--orange);}
.note-card li strong{color:var(--navy);}

.footer-note{font-size:11px;color:#a3aec2;text-align:center;margin-top:32px;}
@media(max-width:600px){.kpi-grid{grid-template-columns:1fr;}.page{padding:6px 14px 30px;}}
</style>
</head>
<body>

<div class="header">
  <div class="header-left">
    <h1>Dashboard Agosto 2026 · AustraliaPRO</h1>
    <p>Broadcast de correo + Rayos X Migratorio (CRM) · Datos manuales</p>
  </div>
  <span class="badge-cache">Corte 19 ago 2026</span>
</div>

<div class="page">
  <div class="section-label">Resumen del mes</div>
  <div class="kpi-grid">
    <div class="kcard k1"><div class="klabel">Correos enviados</div><div class="kval">5</div><div class="ksub">5.330 contactos por envío aprox.</div></div>
    <div class="kcard k2"><div class="klabel">Open rate ponderado</div><div class="kval">20.3%</div><div class="ksub">Sobre 5 broadcasts</div></div>
    <div class="kcard k1"><div class="klabel">Registros Rayos X</div><div class="kval">4</div><div class="ksub">1 no elegible, 1 no asistió, 2 ventas</div></div>
    <div class="kcard k3"><div class="klabel">Consultorías vendidas</div><div class="kval">2</div><div class="ksub">Consultoría Estándar</div></div>
    <div class="kcard k4"><div class="klabel">Ingreso del mes</div><div class="kval">$598</div><div class="ksub">AUD + GST · 2 × $299</div></div>
  </div>

  <div class="section-label">Lectura del mes</div>
  <div class="insight-card">
    <span class="tag">Punto clave</span>
    <h3>RAYOSX_agosto_2 y _3 traen mejor click rate, pero el cierre viene del embudo completo de la llamada</h3>
    <p>Los tres envíos de la serie <strong>RAYOSX</strong> tienen click rate muy superior a los envíos generales (2.49% y 2.39% frente a 0.44% y 0.28%), lo que confirma que el asunto y el enfoque de esa serie generan más intención de agendar la llamada exploratoria.</p>
    <p>De los <span class="big">4 registros</span> que llegaron al pipeline Rayos X Migratorio en agosto, <strong>1 no calificó</strong> (Daniel Alarcón), <strong>1 agendó y no asistió</strong> (Hasmuddin Djamal) y <strong>2 avanzaron a Consultoría Estándar</strong> (Habiba Salem y Carlota Lameiro Vigo), cada una por AUD $299 + GST.</p>
    <div class="note">
      <strong>Con qué cautela leerlo:</strong> todos los negocios del CRM llegan con la misma UTM genérica (<code>email / organic / news / australiapro / rayosx</code>), no una UTM por correo individual. No podemos todavía atribuir qué broadcast específico originó cada uno de los 4 registros; solo sabemos que vinieron del canal email/newsletter en general. Para resolver esto hace falta UTM específica por envío, igual que ya se implementó en el dashboard de SkillsPRO.
    </div>
  </div>

  <div class="section-label">Rendimiento de los correos enviados</div>
  <div class="charts-row">
    <div class="ccard">
      <div class="ctitle">Open rate por correo</div>
      <div class="csub">5 broadcasts de agosto</div>
      <div class="cwrap" style="height:275px"><canvas id="cOpen"></canvas></div>
    </div>
    <div class="ccard">
      <div class="ctitle">Click rate por correo</div>
      <div class="csub">La serie RAYOSX destaca sobre el resto</div>
      <div class="cwrap" style="height:275px"><canvas id="cClick"></canvas></div>
    </div>
  </div>

  <div class="section-label">Embudo Rayos X Migratorio</div>
  <div class="charts-row-2">
    <div class="ccard">
      <div class="ctitle">De agendamiento a venta</div>
      <div class="csub">4 registros del mes</div>
      <div class="cwrap" style="height:260px"><canvas id="cFunnel"></canvas></div>
    </div>
    <div class="ccard">
      <div class="ctitle">Estado actual de los 4 registros</div>
      <div class="csub">Etapa del pipeline al corte</div>
      <div class="cwrap" style="height:260px"><canvas id="cEstado"></canvas></div>
    </div>
  </div>

  <div class="section-label">Broadcast · métricas por correo enviado</div>
  <div class="table-card"><div class="table-scroll"><table>
    <thead><tr id="theadBroadcast"></tr></thead>
    <tbody id="tbodyBroadcast"></tbody>
  </table></div></div>
  <div class="note-card" style="margin-top:14px;border-left-color:var(--cyan)">
    <div class="note-title">Asuntos pendientes</div>
    <div class="note-intro" style="margin-bottom:0">Falta incorporar el asunto de cada correo en la tabla de broadcast. Queda como pendiente para completar en cuanto se confirmen.</div>
  </div>

  <div class="section-label">Detalle Rayos X Migratorio · CRM</div>
  <div class="table-card"><div class="table-scroll"><table>
    <thead><tr id="theadCrm"></tr></thead>
    <tbody id="tbodyCrm"></tbody>
  </table></div></div>

  <div class="section-label">Problemáticas a resolver</div>
  <div class="note-card">
    <div class="note-title">Limitaciones actuales de medición</div>
    <div class="note-intro">El panel se limita a lo que hoy podemos registrar de forma confiable entre el broadcast de correo y el CRM de Rayos X Migratorio.</div>
    <ul>
      <li><strong>No hay UTM específica por correo en el CRM.</strong> Los 4 registros de agosto comparten la misma UTM genérica (<code>australiapro / rayosx</code>), así que no podemos atribuir cada agendamiento a un broadcast puntual.</li>
      <li><strong>El asunto de cada correo todavía no está cargado</strong> en la tabla de broadcast.</li>
      <li><strong>Órdenes y revenue del broadcast salen vacíos.</strong> El ingreso de las 2 ventas ($598 AUD + GST) se registra en el CRM, pero no está conectado automáticamente con el correo que las originó.</li>
      <li><strong>Muestra pequeña.</strong> Con solo 4 registros en el mes, las lecturas de conversión (2 de 4 en total, 2 de 3 entre los elegibles) todavía tienen bajo volumen para sacar conclusiones firmes sobre qué mensaje convierte mejor.</li>
    </ul>
  </div>

  <p class="footer-note">Dashboard AustraliaPRO by Entrelingo · Agosto 2026 en curso · Datos de broadcast de correo y CRM Rayos X Migratorio</p>
</div>

<script>
/* ---------- BROADCAST ---------- */
const BROADCAST_COLS=['Nombre','Creado','Enviado','Contactos','Enviados','Open rate','Click rate','Órdenes','Revenue','Estado'];
const BROADCAST=[
  {name:'AustraliaPRO_agosto_1',created:'6 ago 2026 10:12 am',exec:'7 ago 2026 7:58 am',contacts:'1.072',sent:'1.072',open:'24.06%',click:'0.44%',orders:'–',revenue:'–',status:'Completed'},
  {name:'AustraliaPRO_agosto_encuesta',created:'10 ago 2026 11:55 am',exec:'10 ago 2026 12:31 pm',contacts:'1.045',sent:'1.044',open:'23.05%',click:'0.28%',orders:'–',revenue:'–',status:'Completed'},
  {name:'AustraliaPRO_RAYOSX_agosto_2',created:'13 ago 2026 8:46 am',exec:'13 ago 2026 9:10 am',contacts:'1.072',sent:'1.072',open:'20.53%',click:'2.39%',orders:'–',revenue:'–',status:'Completed'},
  {name:'AustraliaPRO_RAYOSX_agosto_3',created:'13 ago 2026 9:13 am',exec:'14 ago 2026 9:30 am',contacts:'1.072',sent:'1.072',open:'18.59%',click:'1.47%',orders:'–',revenue:'–',status:'Completed'},
  {name:'AustraliaPRO_RAYOSX_agosto_4',created:'18 ago 2026 12:28 pm',exec:'18 ago 2026 12:40 pm',contacts:'1.069',sent:'1.069',open:'15.88%',click:'2.49%',orders:'–',revenue:'–',status:'Completed'}
];
document.getElementById('theadBroadcast').innerHTML=BROADCAST_COLS.map(c=>'<th>'+c+'</th>').join('');
document.getElementById('tbodyBroadcast').innerHTML=BROADCAST.map(b=>{
  const est='<span class="pill p-completed">Completed</span>';
  return '<tr>'+
    '<td class="wrap"><strong style="color:#234283">'+b.name+'</strong></td>'+
    '<td>'+b.created+'</td>'+
    '<td>'+b.exec+'</td>'+
    '<td class="num">'+b.contacts+'</td>'+
    '<td class="num">'+b.sent+'</td>'+
    '<td class="num">'+b.open+'</td>'+
    '<td class="num">'+b.click+'</td>'+
    '<td class="num muted">'+b.orders+'</td>'+
    '<td class="num muted">'+b.revenue+'</td>'+
    '<td>'+est+'</td>'+
  '</tr>';
}).join('');

/* ---------- CRM RAYOS X ---------- */
const CRM_COLS=['Nombre','Contacto','Etapa','Etapa anterior','Responsable','Área profesional','Fecha creación','Fecha sesión','Canal Clientify','Ingreso'];
const CRM=[
  {nombre:'Daniel Alarcón Calderón',contacto:'danielalarcon.electricista@gmail.com',etapa:'No elegible Rayos X',anterior:'–',resp:'Nathanael Fernández',area:'Otros',creacion:'7 ago 2026',sesion:'14 ago 2026',canal:'inbox_whatsapp',ingreso:'–',pill:'p-noelegible'},
  {nombre:'Habiba Salem',contacto:'juanguillermo.artiaga@gmail.com',etapa:'Consultoría migratoria',anterior:'Compró',resp:'Nathanael Fernández',area:'Educación, artes y cocina',creacion:'7 ago 2026',sesion:'8 ago 2026 10:00',canal:'import',ingreso:'$299 + GST',pill:'p-consultoria'},
  {nombre:'Hasmuddin Djamal',contacto:'hasmuddinffz@gmail.com',etapa:'No se ha presentado',anterior:'Elegible Rayos X',resp:'Nathanael Fernández',area:'Construcción, Diseño y Drafting',creacion:'7 ago 2026',sesion:'8 ago 2026 11:20',canal:'–',ingreso:'–',pill:'p-noasistio'},
  {nombre:'Carlota Lameiro Vigo',contacto:'carlotalameiro.vigo@gmail.com',etapa:'Consultoría migratoria',anterior:'Compró',resp:'Nathanael Fernández',area:'Terapia y Servicios sociales',creacion:'6 ago 2026',sesion:'10 ago 2026 8:00',canal:'–',ingreso:'$299 + GST',pill:'p-consultoria'}
];
document.getElementById('theadCrm').innerHTML=CRM_COLS.map(c=>'<th>'+c+'</th>').join('');
document.getElementById('tbodyCrm').innerHTML=CRM.map(r=>{
  return '<tr>'+
    '<td class="wrap"><strong style="color:#234283">'+r.nombre+'</strong></td>'+
    '<td class="wrap">'+r.contacto+'</td>'+
    '<td><span class="pill '+r.pill+'">'+r.etapa+'</span></td>'+
    '<td>'+r.anterior+'</td>'+
    '<td>'+r.resp+'</td>'+
    '<td class="wrap">'+r.area+'</td>'+
    '<td>'+r.creacion+'</td>'+
    '<td>'+r.sesion+'</td>'+
    '<td>'+r.canal+'</td>'+
    '<td class="num">'+r.ingreso+'</td>'+
  '</tr>';
}).join('');

/* ---------- CHARTS ---------- */
Chart.register(ChartDataLabels);
const CFG={responsive:true,maintainAspectRatio:false};
const NAMES=BROADCAST.map(b=>b.name.replace('AustraliaPRO_','').replace('_agosto',''));

new Chart(document.getElementById('cOpen'),{type:'bar',
  data:{labels:NAMES,datasets:[{data:BROADCAST.map(b=>parseFloat(b.open)),backgroundColor:'#234283',borderRadius:8}]},
  options:{...CFG,plugins:{legend:{display:false},datalabels:{anchor:'end',align:'end',color:'#234283',font:{size:12,weight:'bold'},formatter:v=>v+'%'}},
    scales:{x:{ticks:{font:{size:9,weight:'bold'},color:'#7686a1'},grid:{display:false}},y:{beginAtZero:true,ticks:{color:'#a3aec2'},grid:{color:'#eef1f7'},afterDataLimits(s){s.max=s.max+4;}}}}});

new Chart(document.getElementById('cClick'),{type:'bar',
  data:{labels:NAMES,datasets:[{data:BROADCAST.map(b=>parseFloat(b.click)),backgroundColor:BROADCAST.map(b=>b.name.includes('RAYOSX')?'#209ef5':'#c7d1e6'),borderRadius:8}]},
  options:{...CFG,plugins:{legend:{display:false},datalabels:{anchor:'end',align:'end',color:'#0d7fc9',font:{size:12,weight:'bold'},formatter:v=>v+'%'}},
    scales:{x:{ticks:{font:{size:9,weight:'bold'},color:'#7686a1'},grid:{display:false}},y:{beginAtZero:true,ticks:{color:'#a3aec2'},grid:{color:'#eef1f7'},afterDataLimits(s){s.max=s.max+0.5;}}}}});

new Chart(document.getElementById('cFunnel'),{type:'bar',
  data:{labels:['Agendaron','Elegibles','Asistieron','Ventas'],datasets:[{data:[4,3,2,2],backgroundColor:['#234283','#209ef5','#5fc0fb','#3ecf8e'],borderRadius:8}]},
  options:{...CFG,indexAxis:'y',plugins:{legend:{display:false},datalabels:{anchor:'end',align:'end',color:'#234283',font:{size:12,weight:'bold'},formatter:(v,c)=>c.dataIndex===0?v:v+'  ('+(v/4*100).toFixed(0)+'%)'}},
    scales:{x:{beginAtZero:true,ticks:{stepSize:1,color:'#a3aec2'},grid:{color:'#eef1f7'},afterDataLimits(s){s.max=s.max+1;}},y:{ticks:{font:{size:11,weight:'bold'},color:'#556277'},grid:{display:false}}}}});

new Chart(document.getElementById('cEstado'),{type:'doughnut',
  data:{labels:['No elegible','No se presentó','Consultoría migratoria (venta)'],datasets:[{data:[1,1,2],backgroundColor:['#f4915e','#ffb020','#3ecf8e'],borderWidth:3,borderColor:'#fff'}]},
  options:{...CFG,cutout:'55%',plugins:{legend:{position:'bottom',labels:{font:{size:10},boxWidth:12,padding:10,color:'#556277',usePointStyle:true,pointStyle:'circle'}},datalabels:{color:'#fff',font:{size:14,weight:'bold'},formatter:v=>v||''}}}});
</script>
</body>
</html>
