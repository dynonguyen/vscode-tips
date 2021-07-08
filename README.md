<h1 align="center"> Tối ưu hoá công việc trên Visual Code </h1>

<!-- banner -->
<div align="center">
  <img  src="./images/banner.png" height="200" width="450" />
</div>

<!-- Mô tả -->
<br />

# 🥰 MÔ TẢ

> Sau thời gian làm việc với VSCode IDE thì mình tích góp được một vài cách làm việc nhanh hơn với IDE này. Dưới đây là tất cả những Extensions, Settings, Tips mà mình biết về VScode, mong rằng bài viết này sẽ giúp mọi người tối ưu hoá được công việc, cũng như tạo được nguồn cảm hứng khi làm việc trên IDE này nhé.
> Nếu thấy hay hãy thả cho mình một sao nhé hehe 😉

<!-- Extensions -->
<br/>

# ⚒ Các Extension mình đã và đang dùng

<!-- Visual Studio IntelliCode -->
<details>
  <summary>
    1. Visual Studio IntelliCode
  </summary>

  <br/>

> Ext này hình như mặc định đã được cài thì phải. Còn nếu ae nào bị mất thì có thể cài lại nhé. Nó sẽ suggest code cho ae để ae code nhanh hơn.

<div align="center">
  <img src="./images/vs-intelli-code.png">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

</details>

<!-- dracula theme -->
<details>
  <summary>
    2. Dracula Theme
  </summary>

<br />

> Nói về Dracula theme thì chắc đây cũng chính là theme quốc dân của bao ae coder đang dùng VScode nhỉ 😁. Đây là theme mình đang dùng, cách tuỳ chỉnh lại mình sẽ nói dưới phần cài đặt nhé 🤗

> Hoặc ae có thể tải bản đã setting sẵn của anh Trần Anh Tuấn Evondev nhé.

<div align="center">
  <img src="./images/daracula-theme.jpg" />
</div>

🔗 [Link tải bản gốc](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)

🔗 [Link tải bản của Evondev](https://marketplace.visualstudio.com/items?itemName=evondev.dracula-high-contrast)

</details>

<!-- advanced new file -->
<details>
  <summary>
    3. Advanced-new-file
  </summary>
  <br/>

> Có bạn giờ bạn cảm thấy khó khăn khi phải tìm đến 1 thư mục con nằm trong thư mục con >> nằm trong thư mục con ... chỉ để tạo 1 file mới chưa? 😥 Nếu rồi thì đây chính là giải pháp cho ae đây 🙄 Extension "advanced-new-file" !

> Bạn chỉ cần dùng câu lệnh bằng cách bấm "Ctrl + Shift + P", Nhập câu command và chọn đường dẫn (Bạn chỉ cần nhập tắt, Ext sẽ giúp bạn đến đúng folder đó). Ngoài ra bạn có thể tạo folder bằng cách thêm "/" sau tên nhé.

> Còn muốn nhanh hơn thì xem phần cài đặt shorcut bên dưới nhé 😊

<div align="center">
  <img src="./images/advanced-new-file.gif" />
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)

</details>

<!-- file utils -->
<details>
  <summary>
    4. File Utils
  </summary>
  <br/>

> Cũng như ext trên, ext này giúp bạn có thể đổi tên file, xoá tên file ngay lập tức mà không cần tìm đến cây thư mục của VSCode nữa.

> Kết hợp với ext "advanced-new-file" thì bạn có thể bỏ luôn cây thư mục bên kia rồi hehe. Không cần dùng chuột như Vim luôn nè 😉

<div align="center">
  <img src="./images/file-utils.gif" />
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils)

</details>

<!-- auto import -->
<details>
  <summary>
    5. Auto import
  </summary>

  <br/>

> Ext này sẽ giúp ae tự động tìm kiếm đường dẫn và import file. Nếu nó không tự động suggest thì ae có thể nhấn "Ctrl + Space" nhé.

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)

</details>

<!-- auto rename tag -->
<details>
  <summary>
    6. Auto rename tag
  </summary>

  <br/>

> Ext này rất hữu ích cho ae Front-end. Khi cài đặt xong, ae chỉ cần sửa thẻ mở của 1 tag html (jsx) thì phần thẻ đóng cũng sẽ tự đổi theo 😗.

<div align="center">
  <img src="./images/auto-rename-tag.gif" />
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

</details>

<!-- Autoprefixer -->
<details>
  <summary>
    7. Autoprefixer
  </summary>

  <br/>

> Ext này giúp ae code css, sass tự thêm các prefix cho từng trình duyệt khác nhau (vd: --webkit-, --ms-). Chỉ cần khi code xong, ae chạy command "Autoprefixer"

<div align="center">
  <img src="./images/auto-prefixer.gif" />
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-autoprefixer)

</details>

<!-- Better comments -->
<details>
  <summary>
    8. Better comment
  </summary>
  <br/>

> Ext này giúp ae thay đổi màu comment dựa trên ý nghĩa của comment đó. Chỉ cần nhìn vào màu comment là biết ngay nó làm cái chi, có ý nghĩa gì 🤩

<div align="center">
  <img src="./images/better-comment.png" />
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

</details>

<!-- Bracket Pair Colorizer -->
<details>
  <summary>
    9. Bracket Pair Colorizer 2
  </summary>

  <br/>

> Ext này giúp tự động thay đổi màu cho các cặp ngoặc, việc này giúp chúng ta dễ dàng nhận biết các scope khác nhau dựa trên màu sắc của chúng.

<div align="center">
  <img src="./images/bracket-color.png" />
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

</details>

<!-- Code spell checker -->
<details>
  <summary>
    10. Code Spell Checker
  </summary>

  <br/>

> Người ta nói, một lý luận của bạn đều trở nên vô nghĩa nếu bạn sai "trính tã". Vì thế, đừng để ae chí cốt code chung chúng ta chửi chúng ta code ngu chỉ vì lỗi chính tả. Cài ngay Ext này để nó nhắc lỗi chính tả cho bạn.

<div align="center">
  <img src="./images/code-spell-checker.gif" />
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

</details>

<!-- code highlight -->
<details>
  <summary>
    11. Code Highlight
  </summary>

  <br/>

> Ext sẽ giúp phát hiện ra những đoạn code có chưa mã màu và tô đúng màu đó cho bạn.

<div align="center">
  <img src="./images/code-highlight.gif" />
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

</details>

<!-- 12. EditorConfig -->
<details>
  <summary>
    12. EditorConfig for VS Code
  </summary>

  <br/>

> Ext này sẽ giúp bạn tạo cái file trong dự án cùng một format với nhau, ví dụ như Spaces: 2, tab: 4, LF, trim_trailing_whitespace ... Kết hợp với file .editorconfig thì các người khác trong team cũng tuân theo quy tắc đó.

<div align="center">
  <img src="./images/editorconfig.png">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

</details>

<!-- 13. ESLint -->
<details>
  <summary>
    13. ESLint
  </summary>

  <br/>

> ESLint sẽ giúp chúng ta có thể tạo ra những quy tắc chung trong project, để code của tất cả các file được đồng nhất với nhau. Nó khác với Editorconfig ở chỗ là Editorconfig chỉ tạo những quy tắc về format code, định dạng file. Còn ESLint có thể tạo nhiều rule về code hơn.

🔗 [Link tải Extensionhttps://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint

</details>

<!-- 14. Prettier -->
<details>
  <summary>
    14. Prettier - Code Formater
  </summary>

  <br/>

> Prettier là 1 trình Formater hoàn hảo, nó giúp chúng ta format code, auto format và đặc biệt là nó có thể kết hợp với các quy tắc của Editor config và ESLint để Format (Nhưng chúng ta phải câu hình chúng).

<div align="center">
  <img src="./images/prettier.png">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

🔗 [Tìm hiểu thêm về Prettier](https://prettier.io/docs/en/options.html)

</details>

<!-- ES7 React/Redux/GraphQL/React Native Snippet  -->
<details>
  <summary>
    15. ES7 React/Redux/GraphQL/React Native Snippet  
  </summary>

  <br/>

> Bộ snippet hữu dụng cho React dev, giúp ae tạo bộ khung chương trình 1 cách nhanh chóng.

<div align="center">
  <img src="./images/es7-react.png">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)

</details>

<!-- 16. Git Blame / Git History -->
<details>
  <summary>
    16. Git Blame / Git History / Git Lens
  </summary>

  <br/>

> 3 Exts Git Blame, Git History, Git Lens có chức năng khá tương đồng nhau. Nó giúp ae có thể xem đoạn lịch sử git trực tiếp tai dòng code đó, xem branch hiện tại, các thay đổi của file, merge file, ...

> Bản thân mình thì mình thích Git Blame hơn vì nó tối giản, gọn nhẹ hơn. Ae có thể thử cả 3 rồi chọn cho mình 1 cái ưng ý nhé 😋

<div align="center">
  <img src="./images/git-blame.gif">
</div>

🔗 [Link tải Git Blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame)

🔗 [Link tải Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

🔗 [Link tải Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)

</details>

<!-- 17. Highlight Matching Tag -->
<details>
  <summary>
    17. Highlight Matching Tag
  </summary>

  <br/>

> Ext này giúp chúng ta tìm nhanh thẻ đóng của 1 thẻ mở bằng cách đưa con trỏ đến thẻ mở, Ext sẽ tự tìm thẻ đóng cho chúng ta. Ae cũng có thể custom lại màu highlight tuỳ thích.

<div align="center">
  <img src="./images/highlight-matching-tag.gif">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)

</details>

<!-- 18. htmltagwrap -->
<details>
  <summary>
    18. htmltagwrap
  </summary>

  <br/>

> Như cái tên của nó, Ext này sẽ giúp ae wrap 1 cặp thẻ bao 1 đoạn code html (jsx) lại một cách nhanh chóng (mặt định là tổ hợp "Alt + W"). Thay vì ae phải viết 1 thẻ mở, rồi tìm đến cuối đoạn để đóng thẻ đó lại thì chỉ cần bôi đen đoạn code rồi bấm tổ hợp phím. Ae cũng có thể lựa chọn cặp thẻ để bao lại là thẻ gì.

<div align="center">
  <img src="./images/htmltagwrap.gif">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=bradgashler.htmltagwrap)

</details>

<!-- 19. Indent-rainbow -->
<details>
  <summary>
    19. indent-rainbow
  </summary>

  <br/>

> Ext giúp tô màu cho các tab đầu dòng của chúng ta theo kiểu rainbow, giúp phân biệt các dòng code và scope code dễ dàng hơn.

<div align="center">
  <img src="./images/indent-rainbow.png">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

</details>

<!-- 20. JavaScript (ES6) code snippet -->
<details>
  <summary>
    20. JavaScript (ES6) code snippet
  </summary>

  <br/>

> Ae nào code Javascript thì chắc hẳn đều biết đến Ext này, bộ snippet cực hữu dụng cho code JS.

<div align="center">
  <img src="./images/js-code-snippet.png">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

</details>

<!-- 21. Live Server -->
<details>
  <summary>
    21. Live Server
  </summary>

  <br/>

> Live Server Ext sẽ giúp chúng ta tạo một hot reload server khi code html, css, js. Chỉ cần save lại là server sẽ tự reload và cập nhật lại trên browser.

<div align="center">
  <img src="./images/live-server.gif">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

</details>

<!-- 22. Material Icon Theme / vscode-icons -->
<details>
  <summary>
    22. Material Icon Theme / vscode-icons
  </summary>

  <br/>

> 2 Ext này giúp ta thêm icon vào các thư mục, file bên cây thư mục của VSCode, giúp chúng ta dễ dàng phân biệt các file, folder với nhau.

<div align="center">
  <img src="./images/vscode-icons.gif">
</div>

<br />

<div align="center">
  <img src="./images/material-icons.png">
</div>

🔗 [Link tải Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

🔗 [Link tải vs-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

</details>

<!-- 23. Path Intellisense -->
<details>
  <summary>
    23. Path Intellisense
  </summary>

  <br/>

> Ext này sẽ auto suggest đường dẫn khi bạn gõ đường dẫn.

<div align="center">
  <img src="./images/path-intellisense.gif">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

</details>

<!-- 24. Project Manager -->
<details>
  <summary>
    24. Project Manager
  </summary>

  <br/>

> Ext này giúp ae lưu trữ các đường dẫn đến các thư mục chứa các project mà ae đang code. Vì thể, việc mở 1 project sẽ trở nên nhanh chóng hơn rất nhiều.

<div align="center">
  <img src="./images/project-manager.png">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)

</details>

<!-- 25. React PropTypes Generate -->
<details>
  <summary>
    25. React PropTypes Generate
  </summary>

  <br/>

> Nếu ae đang code React và dùng Proptype thì Ext này sẽ giúp ae tạo nhanh chóng proptype cho component.

<div align="center">
  <img src="./images/react-proptypes.gif">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=suming.react-proptypes-generate)

</details>

<!-- 26. REST Client -->
<details>
  <summary>
    26. REST Client
  </summary>

  <br/>

> Ext giúp chúng ta có thể test REST API dễ dàng chỉ với vài dòng code ngay trên VSCode mà không cần phải dùng đến Postman nữa.

<div align="center">
  <img src="./images/rest-client.gif">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

</details>

<!-- 27. SCSS Formater -->
<details>
  <summary>
    27. SCSS Formater
  </summary>

  <br/>

> Ext giúp format code css và scss

<div align="center">
  <img src="./images/scss-formater.gif">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=sibiraj-s.vscode-scss-formatter)

</details>

<!-- 28. Power Mode -->
<details>
  <summary>
    28. Power Mode
  </summary>

  <br/>

> Ext này sẽ tạo hiệU ứng khi ta viết code, giúp ae có cảm hứng làm việc hơn. Nhưng nó có thể gây chậm máy, lag nên ae cân nhắc. Buồn buồn hả bật lên 😎

<div align="center">
  <img src="./images/power-mode.gif">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode)

</details>

<!-- 29. Import cost -->
<details>
  <summary>
    29. Import cost
  </summary>

  <br/>

> Ext sẽ hiển thị size của các thư viện mà ae import vào, từ đó ae cân nhắc xem có nên thêm thư viện đó vào hay không.

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)

</details>

<!-- 30. Bookmarks -->
<details>
  <summary>
    30. Bookmarks
  </summary>

  <br/>

> Ext giúp chúng ta đặt các bookmark tại các dòng code cần lưu ý. Ext này đặc biết hữu dụng khi luồng code của chúng ta khá phức tạp, chia ở nhiều file. Khi Debug ta sẽ đánh dấu lại các dòng code đó.

<div align="center">
  <img src="./images/bookmarks.png">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)

</details>

<!-- 31. Remote - WSL -->
<details>
  <summary>
    31. Setting Sync
  </summary>

  <br/>

> Sau khi cài đống extensions trên và những cài đặt ở dưới đây, thì chúng ta có thể lưu trữ nó trên Github Gist và dùng Setting Sync để đồng bộ lại. Trong trường hợp, phải dùng máy tính khác hoặc phải cài lại phần mềm thì Ext này sẽ giúp những cài đặt chúng ta không bị mất đi.

<div align="center">
  <img src="./images/setting-sync.png">
</div>

🔗 [Link tải Extension](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)

</details>

<!-- Bonus: Tabnine AI Code & GitHub Copilot -->
<details>
  <summary>
    Bonus: Tabnine AI Code & GitHub Copilot
  </summary>

  <br/>

> 2 thanh niên AI đang làm mưa làm gió hiện nay. Ae có thể tìm hiểu thêm nhé.

🔗 [Link tải Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)

🔗 [Link tải Github Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

</details>

<!-- setting -->
<br />

# ⚙ Các cài đặt Visual Code

<!-- shortcut -->
<br />

# 🐱‍👤 Snippet

# ⌨ Các shortcut hữu dụng trong Visual Code
