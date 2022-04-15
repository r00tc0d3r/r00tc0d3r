<h1 align="center">Hi 👋, I'm Rodrigo Gilabert</h1>
<h2 align="center">Full Stack Developer and a Future Systems Engineer</h2>

<br />

- 🔭 I’m currently working as a **Full Stack Developer**

- 🌱 I’m want to learn **Java and Spring**

- 📫 How to reach me **rgilabert07@gmail.com**

<br />
<h2 align="center">My Tech Stack</h2>
<div style="
background-color: #EBE7C2;
padding: 20px;
border-radius: 90px;
border-width: 3px;
border-style: solid;
border-color: cyan;
">
  <p align="center"> 
      <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://reactjs.org/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="70" height="70" padding=200px/> 
      </a> 
      <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="70" height="70"/> 
      </a> 
      <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="70" height="70"/> 
      </a> 
      <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://nodejs.org" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="70" height="70"/> 
      </a> 
      <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://expressjs.com" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="70" height="70"/> 
      </a>

  </p>
  <p align="center">
    <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="70" height="70"/> 
    </a> 
    <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://www.mysql.com/" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="70" height="70"/> 
    </a> 
    <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://jestjs.io" target="_blank" rel="noreferrer"> 
      <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="70" height="70"/> 
    </a> 
    <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://github.com/puppeteer/puppeteer" target="_blank" rel="noreferrer"> 
      <img src="https://www.vectorlogo.zone/logos/pptrdev/pptrdev-official.svg" alt="puppeteer" width="70" height="70"/> 
    </a> 
    <a style="
      padding-top: 10px;
      padding-right: 10px;
      padding-bottom: 10px;
      padding-left: 10px;" href="https://www.linux.org/" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="70" height="70"/> 
    </a>

  </p>
</div>

<h3 style="padding-top: 30px;"align="center">Connect with me:</h4>
<p style="
width: 120px;
height: 120px;
-moz-border-radius: 50%;
-webkit-border-radius: 50%;
border-radius: 50%;
background: #EBE7C2;
margin: auto;
line-height: 100px;
border-width: 3px;
border-style: solid;
border-color: cyan;" align="center">
  <a href="https://linkedin.com/in/pablo-rodrigo-gilabert" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="pablo-rodrigo-gilabert" height="70" width="80" /></a>
</p>


" Vim Devicons
if exists("g:loaded_webdevicons")
  call webdevicons#refresh()
endif

" Signify
let g:signify_sign_add = '+'
let g:signify_sign_delete = '-'
let g:signify_sign_change = '~'
let g:signify_sign_show_count = 0
let g:signify_sign_show_text = 1

highlight SignifySignAdd                  ctermbg=green                guibg=#00ff00
highlight SignifySignDelete ctermfg=black ctermbg=red    guifg=#ffffff guibg=#ff0000
highlight SignifySignChange ctermfg=black ctermbg=yellow guifg=#000000 guibg=#ffff00

" Mapeo de la barra de estado airline
let g:airline#extensions#tabline#enabled = 1
let g:airline#extensions#tabline#fnamemod = ':t'
let g:airline_powerline_fonts = 1
let g:airline_theme="tomorrow"

" Configuring the highlight devicons
let g:NERDTreeFileExtensionHighlightFullName = 1
let g:NERDTreeExactMatchHighlightFullName = 1
let g:NERDTreePatternMatchHighlightFullName = 1

" Prettier configuration for vim
command! -nargs=0 Prettier :call CocAction('runCommand', 'prettier.formatFile')

" Terminal split
vnoremap <c-t> :split<CR>:terminal<CR>:resize 15<CR>
nnoremap <c-t> :split<CR>:terminal<CR>:resize 15<CR>
