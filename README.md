# モブプログラミングパターン

モブプログラミングとは、チーム全員が同じ時間に同じものを共創していくソフトウェア制作の手法です。効果的なモブの中心には、
最高のソフトウェアをできるだけ早く提供するために、お互いを尊重しながら働く人々がいます。
効果的なモブプログラミングは、チームメイト間の効果的なコミュニケーションから生まれます。 
当然のことながら、対話のスタイルはチームごと、状況ごとに大きく異なります。 そのため、「モブプラグラミングを行うための一つの筋道」というものはありません。 
そこで、強力なパターンカタログが役に立つのです。

パターンとは、特定の状況下で特定の問題への対応として生まれた再現可能な解決策のことです。 パターンカタログは、道具箱に入った様々な道具である、と言えます。
信頼のおける金槌を普段は使いたくなるかもしれませんが、仕事に適したツールを選ぶことで、仕事が楽になるだけでなく、最終的な結果もより良いものになります。 
大切なのは、そのパターンをいつ、どのように使うかというのを知っていることです。

モブプログラミングは、まだ比較的若い手法です。 我々は皆モブプログラミングをよりよく実践する方法を学んでいる最中です。
モブプログラミングは非常に強力な手法であると判断したとしても、それをうまくやるためには練習が必要です。 
このリポジトリの目的は、私たちがこれまでに発見したパターンを記録することで、結果的にそれが、他のチームがモブプログラミングを始める際の出発点として役立つことを期待しています。

## パターン

| パターン                     | カテゴリ      | 解説                                                                                                                                                                                                                              |
|----------------------------|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ファシリテータ                | ロール      | チームの集中力を維持したり、意見の相違を解決するのを助ける役割。  通常、ドライバーはこの役割を担いません。                                                                                             |
| 記録係                  | ロール      | コンテキストやデザインの決定事項などのメモを取る役割。                                                                                                                                            |
| 研究係                 | ロール      | ワークが前に進むために必要な情報をリアルタイムに探す。                                                                                                                                    |
| ナビゲータ                  | ロール      | ドライバーに何をすべきかを指示する役割。現在ドライバーではないモブのメンバーは、ナビゲーターであるとみなされます。ナビゲーターは様々な方法でモブに貢献できます。                                                                     |
| ドライバー                     | ロール      | キーボードに向かう人。ナビゲータが問題を解決するために考えていることを受け取ります。                                                    |
| 悪魔の代弁者           | ロール      | モブによる設計を強化するため、逆の立場に立つナビゲータ。|
| パンチリスト                 | 共同作業 | モブで利用される作用リストで、今何をしているのかを記録し、次何をするのかを選ぶとき使われる。パンチリストはテキストベースでもグラフィカルでもよい。
| 暖簾分け             | 共同作業 |単純作業を完成させるために、主流から分岐したメンバー。暖簾分けしたたメンバーで代替案を作成し、全体で検討を行うこともある。                                                     |
| 助手席             | 共同作業 | 他のナビゲーターを無視して、ひたすらモブの仕事を指示するナビゲーターのこと。                                                                                                                                              |
| Mute your mic              | 共同作業 | A navigator chooses to temporarily remain silent as a navigator to give other navigators a chance to contribute.  Used as a way to kick start a slow mob or prevent one person from dominating the mob.                           |
| Fight Club                 | 共同作業 | A situation in which two or more participants fight over the direction of the mob with total disregard for the guiding principles of mutual respect and consideration.  Extremely harmful to the mob, considered an anti-pattern. |
| Natural Swap               | 共同作業 | A new driver takes the keyboard without prompting by either a member of the mob or timer at a “natural” break in the work, such as after a test passes or a refactoring step is completed.                                        |
| Forced Swap                | 共同作業 | A new driver takes the keyboard after being prompted by either a member of the mob or a timer.                                                                                                                                    |
| Distracted non-Participant | 共同作業 | Navigators who are present in the mob but otherwise do not participate, perhaps distracted by other work.                                                                                                                         |
| Thinking Out Loud          | 進行       | The driver articulates their current thinking as they are the prevailing expert in the room or see the path forward.                                                                                                              |
| Tell me what to write      | 進行       | A prompt drivers will sometimes use to engage help from navigators, inviting someone from the mob to direct the driver.                                                                                                           |
| Driving on Autopilot       | 進行       | A driver who proceeds without inputs from the rest of the mob.                                                                                                                                                                    |
| Plowing Through            | 進行       | A driver who, with the support of the mob, works on the task at hand with the intent of completing it as quickly and painlessly as possible.  Often combined with the thinking out loud pattern.                                  |




## Additional Resources

[Ars16] Arsenovski, Danijel.  “Swarm: Beyond pair, beyond Scrum,”
Proceedings from Agile2016, August 2016,
https://www.agilealliance.org/resources/experience-reports/swarm-beyond-pair-beyond-scrum/, retrieved May 24, 2019.

[Fre18] Freudenberg, Sal and Wynne, Matt. “The Surprisingly Inclusive Benefits of Mob Programming,”
Proceedings from XP 2018, May 2018,
https://www.agilealliance.org/resources/experience-reports/the-surprisingly-inclusive-benefits-of-mob-programming/, retrieved May 24, 2019.

[Ham18] Hamid,Amr Noaman Abdel. “Experimenting with Mob-Programming,”
Proceedings from Agile2018, August 2018,
https://www.agilealliance.org/resources/experience-reports/experimenting-with-mob-programming/, retrieved May 24, 2019.

[Kee18] Keeling, Michael and Runde, Joe. “Share the Load: Distributing Design Authority with Lightweight Decision Records,” 
Proceedings from Agile2018, August 2018,
https://www.agilealliance.org/resources/experience-reports/distribute-design-authority-with-architecture-decision-records/ retrieved May 24, 2019.

[Kee19] Keeling, Michael and Runde, Joe. “Harvesting Mob Programming Patters: Observing How we Work,”
Agile Alliance Curated Experience Report, July 2019,
https://www.agilealliance.org/resources/experience-reports/harvesting-mob-programming-patterns-observing-how-we-work/ retrieved July 8, 2019

[Ker15] Kerney, Jason. “Mob Programming -- My First Team,”
Proceedings from Agile2015, August 2015,
https://www.agilealliance.org/resources/experience-reports/mob-programming-my-first-team/, retrieved May 24, 2019.

[Luc17] Lucian, Chris. “Growing the Mob”,
Proceedings from Agile2017, August 2017, 
https://www.agilealliance.org/resources/experience-reports/growing-the-mob/ retrieved May 24, 2019.

[Zui14] Zuil, Woody. “Mob Programming -- a Whole Team Approach,”
Proceedings from Agile2014, August 2014,
https://www.agilealliance.org/resources/experience-reports/mob-programming-agile2014/ retrieved May 24, 2019.
