# guitar-site:
https://mike256520-coder.github.io/guitar-site/

#音樂筆記:
https://mike256520-coder.github.io/guitar-site/music-note/

# 功能說明：
?? 可編輯標題  ?? 可編輯說明  ?? 點圖放大（← → Esc）
?? 學習心得   ? 卡片滑入動畫  ?? Firebase 多人即時同步

每頁主題預設：

吉他基礎入門　2. 音階與節拍　3. 基礎和弦　4. 刷弦技巧　5. 指法練習
進階和弦　7. 歌曲應用　8. 彈唱技巧　9. 即興演奏　10. 完整表演

所有原有功能完整保留：

?? 每頁100格標題與說明均可直接編輯，失焦自動雲端同步
?? Firebase 多人即時同步（100張卡片獨立儲存）
?? 每頁各自有10張的 Lightbox（← → Esc 切換）
? 翻頁時10張卡片依序錯落飛入
?? 頂部導覽列 + 進度條


#如果你想把 Firebase 換成自己的專案，只需要修改 firebaseConfig 裡的 apiKey、authDomain、projectId 三個欄位即可。
# mk520@g..Firebase
# <script>
const firebaseConfig = {
 apiKey: "xxxxxxxxx",
 authDomain: "guitar-site-16251.firebaseapp.com",
 projectId: "guitar-site-16251"
};

firebase.initializeApp(firebaseConfig);
const db = firebase.firestore();
</script>
