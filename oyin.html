<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<title>Shashka</title>
<style>
  body{font-family:sans-serif;text-align:center}
  .board{display:grid;grid-template:repeat(8,60px)/repeat(8,60px);margin:auto}
  .cell{width:60px;height:60px;display:flex;align-items:center;justify-content:center}
  .dark{background:#769656}
  .light{background:#eeeed2}
  .w,.b{width:40px;height:40px;border-radius:50%}
  .w{background:white}
  .b{background:black}
  .selected{outline:3px solid red}
  .move{box-shadow:inset 0 0 0 4px yellow}
</style>
</head>
<body>

<h2>Shashka o‘yini</h2>
<div class="board" id="board"></div>

<script>
let checkersBoard=[
 ["","b","","b","","b","","b"],
 ["b","","b","","b","","b",""],
 ["","b","","b","","b","","b"],
 ["","","","","","","",""],
 ["","","","","","","",""],
 ["w","","w","","w","","w",""],
 ["","w","","w","","w","","w"],
 ["w","","w","","w","","w",""]
];
let turn="w",selected=null,moves=[],history=[],mode="ai";

function draw(){
  const b=document.getElementById("board");
  b.innerHTML="";
  for(let r=0;r<8;r++)for(let c=0;c<8;c++){
    let d=document.createElement("div");
    d.className="cell "+((r+c)%2?"dark":"light");
    d.onclick=()=>clickCell(r,c);
    let v=checkersBoard[r][c];
    if(v){
      let p=document.createElement("div");
      p.className=v.toLowerCase();
      d.appendChild(p);
    }
    b.appendChild(d);
  }
}

function clickCell(r,c){
  if(selected){
    for(let m of moves)
      if(m[0]==r&&m[1]==c){
        checkersBoard[r][c]=checkersBoard[selected[0]][selected[1]];
        checkersBoard[selected[0]][selected[1]]="";
        selected=null;moves=[];
        turn=turn==="w"?"b":"w";
        draw();
        return;
      }
  }
  let v=checkersBoard[r][c];
  if(v&&turn===v){
    selected=[r,c];
    moves=[[r+(v==="w"?-1:1),c-1],[r+(v==="w"?-1:1),c+1]];
  }
}

draw();
</script>
</body>
</html>
