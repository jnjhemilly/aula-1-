* {
  margin: 0;
  padding: 0;
}

body {
    background: blanchedalmond;
    font-family: "Open Sans",sans-serif;
    font-size: 17px;
    line-height: 22px;
}

.titulo-destaque {
  margin: 5, 5, 0, 0;
}

.inline {
  display: inline-flex;
  justify-content: space-around;
}

.produto {
  text-align: center;
  color:#1b1717;
  position: relative;
  border-radius: 10px;
  min-height: 80px;
  background-color:#FFFFFF;
  margin: 25px;  
}

.memoria1 {
  width:40%;
}

.cabtitle {
    background: #65B307;
    display: flex;
	  justify-content: space-around;
    font-family: 'PT Serif', serif;
    padding: 20px 25px;
}

.cabtitlenome {
    text-transform: uppercase;
}


  .footer {
    flex-wrap: wrap;
    box-sizing: border-box;
    padding: 2em;
    gap: 10px;
    display: flex;
    bottom: 0;
    position: relative;
    width: 100%;
    background-color: #65B307;
  }

  .header {
    font-size: 55px;
    color: rgb(26, 14, 14);
    font-family: 'PT Serif', serif;
    flex-basis: 100%;
  }
  
  div.right {
    margin: 0;
    display: flex;
    width: 50%;
    flex-direction: row;
    gap: 10px;
    flex: 1;
  }
  
  div.left {
    flex-basis: 100%;
    margin: 0;
    display: flex;
    gap: 10px;
    width: 50%;
    flex-direction: column;
    flex: 1;
  }
  
  textarea {
    font-family: Azeret Mono;
    box-sizing: border-box;
    color: #1b1717;
    outline: none;
    resize: none;
    border: none;
    padding: 1em;
    border-radius: 10px;
    background-color: #c4b3b3;
  }
  
  .msg {
    flex-basis: 100%;
  }
  
  div.bottom {
    min-width: 0;
    overflow-x: scroll;
    padding-top: 1em;
    gap: 2em;
    color: grey;
    width: 100%;
    flex-basis: 100%;
    display: flex;
  }
  
  .ftrtxt {
    flex-basis: 100%;
    font-size: 15px;
    text-align: center;
    font-family: Rubik Mono One;
    color: rgb(26, 14, 14);
  }
  
  .ftrhead {
    font-size: 35px;
  }
  
  .ftrhead::after,
  .ftrtxt::after {
    content: "\a";
    white-space: pre;
  }
  
  .ftrlinks {
    flex-basis: 1;
  }
  
  hr {
    margin-top: 1em;
    margin-bottom: 1em;
    flex-basis: 100%;
    color: white;
  }
  
  svg {
    fill: white;
    width: 50px;
    height: 50px;
    cursor: pointer;
    transition: 0.5s ease-in-out;
  }
  
  svg:hover {
    transform: scale(1.1);
    fill: grey;
  }
  
  ::placeholder {
    font-family: Azeret Mono;
  }
  
  #start {
    margin-left: auto;
  }
  
  #end {
    margin-right: auto;
  }
  
  ::-webkit-scrollbar {
    height: 5px;
    width: 2px;
  }
  
  ::-webkit-scrollbar-track {
    background: none;
  }
  
  ::-webkit-scrollbar-thumb {
    background: white;
    border-radius: 10px;
    height: 5px;
    width: 2px;
  }
  
  #submitbtn {
    display: none;
    border-radius: 10px;
    border: none;
    font-family: Rubik Mono One;
    font-size: 15px;
    transition: 0.5s;
  }
  
  #submitbtn:hover {
    background-color: var(--lightblk);
    color: var(--blk);
  }
  
  @keyframes slide {
    0% {
      opacity: 0;
      height: 0%;
      border-radius: 10px;
    }
    100% {
      opacity: 1;
      height: 100%;
      border-radius: 10px;
    }
    }
