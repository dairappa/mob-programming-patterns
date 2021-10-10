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
| Facilitator                | Mob role      | Volunteer who helps the group stay focused and to help resolve differences of opinion.  Typically the driver does not take this role.                                                                                             |
| Recorder                   | Mob role      | Volunteers who capture notes such as context or design decisions on behalf of the mob.                                                                                                                                            |
| Researcher                 | Mob role      | Volunteers who seek out information in real-time that is required for the mob to move forward.                                                                                                                                    |
| Navigator                  | Mob role      | Direct the driver in what to do.  Members of the mob not currently driving are assumed to be a navigator.  Navigators can contribute to the mob in many ways.                                                                     |
| Driver                     | Mob role      | The person currently at the keyboard, capturing the thoughts of the navigators as everyone works to solve a particular problem.                                                                                                   |
| Devil’s Advocate           | Mob role      | A navigator who takes a contrarian position to help make the mob’s designs stronger.                                                                                                                                              |
| Punch List                 | Collaboration | A task list used by the mob to track work items and select what to work on next.  Punch lists can be text-based or graphical.                                                                                                     |
| Splinter Group             | Collaboration | One or more members of the mob who break away from the main group to complete a routine task.  Splinter groups can also investigate alternatives for review by the whole mob.                                                     |
| Ridin’ Shotgun             | Collaboration | A navigator who solely dictates the mob’s work to the exclusion of other navigators.                                                                                                                                              |
| Mute your mic              | Collaboration | A navigator chooses to temporarily remain silent as a navigator to give other navigators a chance to contribute.  Used as a way to kick start a slow mob or prevent one person from dominating the mob.                           |
| Fight Club                 | Collaboration | A situation in which two or more participants fight over the direction of the mob with total disregard for the guiding principles of mutual respect and consideration.  Extremely harmful to the mob, considered an anti-pattern. |
| Natural Swap               | Collaboration | A new driver takes the keyboard without prompting by either a member of the mob or timer at a “natural” break in the work, such as after a test passes or a refactoring step is completed.                                        |
| Forced Swap                | Collaboration | A new driver takes the keyboard after being prompted by either a member of the mob or a timer.                                                                                                                                    |
| Distracted non-Participant | Collaboration | Navigators who are present in the mob but otherwise do not participate, perhaps distracted by other work.                                                                                                                         |
| Thinking Out Loud          | Driving       | The driver articulates their current thinking as they are the prevailing expert in the room or see the path forward.                                                                                                              |
| Tell me what to write      | Driving       | A prompt drivers will sometimes use to engage help from navigators, inviting someone from the mob to direct the driver.                                                                                                           |
| Driving on Autopilot       | Driving       | A driver who proceeds without inputs from the rest of the mob.                                                                                                                                                                    |
| Plowing Through            | Driving       | A driver who, with the support of the mob, works on the task at hand with the intent of completing it as quickly and painlessly as possible.  Often combined with the thinking out loud pattern.                                  |




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
