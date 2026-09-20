<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Calcul Bénéfice Taxi</title>
<style>
body{font-family:Arial;background:#f0f2f5;padding:15px}
.card{background:white;padding:20px;border-radius:15px;max-width:400px;margin:auto}
input{width:100%;padding:12px;margin:8px 0 15px 0;border-radius:10px;border:1px solid #ccc}
.btn-bleu{width:100%;padding:14px;background:#1976d2;color:white;border:none;border-radius:10px;font-weight:bold;margin-top:10px}
.result{background:#e8f5e9;padding:15px;border-radius:10px;margin-top:15px;display:none}
</style>
</head>
<body>
<div class="card">
<h2 style="text-align:center">🚕 Taxi Bénéfice</h2>

<label>👤 Client</label><input id="client" placeholder="Nom client">
<label>📏 Distance (km)</label><input id="km" type="number" placeholder="Ex: 15">
<label>⛽ Conso (L/100km)</label><input id="conso" type="number" value="8">
<label>💰 Prix 1L (FC)</label><input id="prix1L" type="number" value="3500">
<label>💵 Prix payé (FC)</label><input id="prixCourse" type="number" placeholder="Ex: 25000">

<label>🕒 Km départ matin</label><input id="kmDepart" type="number" placeholder="Ex: 12300">
<label>🌙 Km arrivée soir</label><input id="kmArrivee" type="number" placeholder="Ex: 12450">

<button class="btn-bleu" onclick="calculerDistance()">📏 Calculer Distance du jour</button>
<p id="resultatDistance" style="text-align:center;font-weight:bold;color:green;margin:10px 0;"></p>

<button class="btn-bleu" onclick="calculer()">CALCULER MON BÉNÉFICE 💰</button>

<div id="resultat" class="result">
<p id="rCarb"></p><p id="rCout"></p><p id="rPrix"></p><p id="rBenef"></p><p id="msg" style="font-weight:bold"></p>
</div>
<button id="btnWa" class="btn-bleu" style="display:none;background:#25D366" onclick="envoyerWA()">Envoyer reçu WhatsApp</button>
</div>

<script>
let dernierRecu="";
function calculer(){
let client=document.getElementById('client').value;
let km=document.getElementById('km').value;
let conso=document.getElementById('conso').value;
let prix1L=document.getElementById('prix1L').value;
let prixCourse=document.getElementById('prixCourse').value;
if(km==0||prixCourse==0){alert("Remplis Distance et Prix payé");return;}
let litres=(km*conso)/100;let cout=litres*prix1L;let benef=prixCourse-cout;
document.getElementById('rCarb').innerText="Carburant: "+litres.toFixed(2)+" L";
document.getElementById('rCout').innerText="Coût: "+cout+" FC";
document.getElementById('rPrix').innerText="Prix payé: "+prixCourse+" FC";
document.getElementById('rBenef').innerText="Bénéfice: "+benef+" FC";
let m=document.getElementById('msg');
if(benef>10000) m.innerText="🔥 Excellent!";
else if(benef>0) m.innerText="👍 Course rentable";
else m.innerText="⚠️ Tu perds!";
dernierRecu=`Bonjour ${client} 👋\n\nReçu course: ${km}km\nBénéfice: ${benef} FC`;
document.getElementById('resultat').style.display='block';
document.getElementById('btnWa').style.display='block';
}
function envoyerWA(){
let url="https://wa.me/?text="+encodeURIComponent(dernierRecu);
window.open(url,"_blank");
}
function calculerDistance(){
let depart=document.getElementById("kmDepart").value;
let arrivee=document.getElementById("kmArrivee").value;
if(depart && arrivee){
let distance=arrivee-depart;
document.getElementById("resultatDistance").innerText="✅ Aujourd'hui: "+distance+" km";
}
}
</script>
</body>
</html>
