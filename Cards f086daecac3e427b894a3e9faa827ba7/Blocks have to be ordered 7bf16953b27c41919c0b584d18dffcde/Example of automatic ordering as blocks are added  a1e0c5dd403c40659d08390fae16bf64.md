# Example of automatic ordering as blocks are added and changed

1. T1 contains N1
2. +S1,2,3 : N1,S1,2,3
3. +Q2.1,2.2,2.3,2.4 : Q1,2,3,4,N1,S2,1,3
4. +C1 + link to Q2.2: C1(1),Q1,3,4,N1,S2,1,3
5. +T2 + link to C1,Q2.4,S3 : T2(3),Q1,3,N1,S2,1
6. +Q2.3 categorized as E1 : T2(3),E1,Q1,N1,S2,1
7. +N2, link to E1: T2(3),E1(1),Q1,N1,S2,1
8. +N2 categorized as C2 : T2(3),C2(1),Q1,N1,S2,1 (E1 and C2 switch level)
9. +link to T1 : switching T2 and T1, T2 with all blocks inside T2 moves to first level, T1 with all blocks not in T2 becomes subtopic in T2

["Versuche erst gar nicht Notizen in ordentlichen Ordnern oder in eindeutigen vorgefassten Kategorien abzulegen. , es gibt in einem Zettelkasten „keine privilegierten Positionen" und „es gibt kein Oben und kein Unten". Die Organisation entwickelt sich organisch." ([Clear 2020:11](zotero://open-pdf/library/items/SFQLIRC3?page=11))](Example%20of%20automatic%20ordering%20as%20blocks%20are%20added%20%20a1e0c5dd403c40659d08390fae16bf64/Versuche%20erst%20gar%20nicht%20Notizen%20in%20ordentlichen%20Or%201cbe67ca0bac4e909276f0e33da32bbf.md)