This project provides text-free graphics, sounds and videos to speed up the translations into any language.

# PSD files
In the `psd_files` folder there are PSD files with english text layers (with H3 like effects). Just edit the text and save as PNG. Images with palettes needs to convert back to indexed in Photoshop (Image -> Mode -> Indexed). Load the palette from corresponding ACT file and select `None` for dithering.

# Dubbing
You can generate dubs in common languages [here](https://huggingface.co/spaces/coqui/xtts) and in almost any language [here](https://huggingface.co/spaces/Brasd99/TTS-Voice-Cloner).

Beware! The order of prologs are tricky!
| Extension | Campaign | File | JSON property | Character |
| --------- | -------- | ---- | ------------- | --------- |
| _Restoration Of Erathia_ | _Long life to the queen_ | `G1A.wav` | `campaign.good1.Good-1a.h3m.prolog` | Catherine IRONFIST |
| _Restoration Of Erathia_ | _Long life to the queen_ | `G1B.wav` | `campaign.good1.Good-1b.h3m.prolog` | Catherine IRONFIST |
| _Restoration Of Erathia_ | _Long life to the queen_ | `G1C.wav` | `campaign.good1.Good-1c.h3m.prolog` | Catherine IRONFIST |
| _Restoration Of Erathia_ | _Dungeons and Devils_ | `E1A.wav` | `campaign.evil1.Evil-1A.h3m.prolog` | Nighon's man |
| _Restoration Of Erathia_ | _Dungeons and Devils_ | `E1B.wav` | `campaign.evil1.Evil-1B.h3m.prolog` | Nighon's man |
| _Restoration Of Erathia_ | _Dungeons and Devils_ | `E1C.wav` | `campaign.evil1.Evil-1c.h3m.prolog` | Nighon's man |
| _Restoration Of Erathia_ | _Liberation_ | `G2A.wav` | `campaign.good2.Good-2a.h3m.prolog` | Catherine IRONFIST |
| _Restoration Of Erathia_ | _Liberation_ | `G2C.wav` | `campaign.good2.Good-2c.h3m.prolog` | Winstan Langer |
| _Restoration Of Erathia_ | _Liberation_ | `G2B.wav` | `campaign.good2.Good-2b.h3m.prolog` | Dorrell |
| _Restoration Of Erathia_ | _Liberation_ | `G2D.wav` | `campaign.good2.Good-2d.h3m.prolog` | Catherine IRONFIST |
| _Restoration Of Erathia_ | _Spoils of War_ | `N1A.wav` | `campaign.neutral1.Neutral-1a.h3m.prolog` | Old woman |
| _Restoration Of Erathia_ | _Spoils of War_ | `N1B.wav` | `campaign.neutral1.Neutral-1b.h3m.prolog` | Old woman |
| _Restoration Of Erathia_ | _Spoils of War_ | `N1C_D.wav` | `campaign.neutral1.Neutral-1c.h3m.prolog` | Old woman |
| _Restoration Of Erathia_ | _Long Live the King_ | `E2A.wav` | `campaign.evil2.Evil-2A.h3m.prolog` | Dead man |
| _Restoration Of Erathia_ | _Long Live the King_ | `E2B.wav` | `campaign.evil2.Evil-2B.h3m.prolog` | Dead man |
| _Restoration Of Erathia_ | _Long Live the King_ | `E2C.wav` | `campaign.evil2.Evil-2C.h3m.prolog` | Dead man |
| _Restoration Of Erathia_ | _Long Live the King_ | `E2D.wav` | `campaign.evil2.Evil-2D.h3m.prolog` | Dead man |
| _Restoration Of Erathia_ | _Long Live the King_ | `E2AE.wav` | `campaign.evil2.Evil-2A.h3m.epilog` |  Dead man |
| _Restoration Of Erathia_ | _Song for the Father_ | `G3A.wav` | `campaign.good3.Good-3A.h3m.prolog` | Catherine IRONFIST |
| _Restoration Of Erathia_ | _Song for the Father_ | `G3B.wav` | `campaign.good3.Good-3B.h3m.prolog` | Catherine IRONFIST |
| _Restoration Of Erathia_ | _Song for the Father_ | `G3C.wav` | `campaign.good3.Good-3C.h3m.prolog` | Catherine IRONFIST |
| _Restoration Of Erathia_ | _Seeds of Discontent_ | `S1A.wav` | `campaign.secret1.Secret-1a.h3m.prolog` | Welnin's man |
| _Restoration Of Erathia_ | _Seeds of Discontent_ | `S1B.wav` | `campaign.secret1.Secret-1b.h3m.prolog` | Welnin's man |
| _Restoration Of Erathia_ | _Seeds of Discontent_ | `S1C.wav` | `campaign.secret1.Secret-1c.h3m.prolog` | Welnin's man |
| _Armageddon's Blade_ | _Armageddon's Blade_ | `ABvoAB1.wav` | `campaign.ab.A- Catherine's Charge.h3m.prolog` | Catherine IRONFIST |
| _Armageddon's Blade_ | _Armageddon's Blade_ | `ABvoAB3.wav` | `campaign.ab.C- Shadows of the Forest.h3m.prolog` | Gelu |
| _Armageddon's Blade_ | _Armageddon's Blade_ | `ABvoAB2.wav` | `campaign.ab.B- Seeking Armageddon.h3m.prolog` | Xeron |
| _Armageddon's Blade_ | _Armageddon's Blade_ | `ABvoAB4.wav` | `campaign.ab.D- Maker of Sorrows.h3m.prolog` | Xeron |
| _Armageddon's Blade_ | _Armageddon's Blade_ | `ABvoAB5.wav` | `campaign.ab.E- Return of the King.h3m.prolog` | Roland IRONFIST |
| _Armageddon's Blade_ | _Armageddon's Blade_ | `ABvoAB6.wav` | `campaign.ab.F- A Blade in the Back.h3m.prolog` | Gelu |
| _Armageddon's Blade_ | _Armageddon's Blade_ | `ABvoAB7.wav` | `campaign.ab.G- To Kill a Hero.h3m.prolog` | Catherine IRONFIST |
| _Armageddon's Blade_ | _Armageddon's Blade_ | `ABvoAB8.wav` | `campaign.ab.H- Oblivion's Edge.h3m.prolog` | Catherine IRONFIST |
| _Armageddon's Blade_ | _Armageddon's Blade_ | `ABvoAB9.wav` | `campaign.ab.H- Oblivion's Edge.h3m.epilog` | Catherine IRONFIST |
| _Armageddon's Blade_ | _Dragon's Blood_ | `ABvoDB1.wav` | `campaign.blood.DB1 Culling the Weak.h3m.prolog` | Mutare |
| _Armageddon's Blade_ | _Dragon's Blood_ | `ABvoDB2.wav` | `campaign.blood.DB2 Savaging the Scavengers.h3m.prolog` | Mutare |
| _Armageddon's Blade_ | _Dragon's Blood_ | `ABvoDB3.wav` | `campaign.blood.DB3 Blood of the Dragon Father.h3m.prolog` | Mutare |
| _Armageddon's Blade_ | _Dragon's Blood_ | `ABvoDB4.wav` | `campaign.blood.DB4 Blood Thirsty.h3m.prolog` | Mutare |
| _Armageddon's Blade_ | _Dragon's Blood_ | `ABvoDB5.wav` | `campaign.blood.DB4 Blood Thirsty.h3m.epilog` | Mutare |
| _Armageddon's Blade_ | _Dragon Slayer_ | `ABvoDS1.wav` | `campaign.slayer.DragonSlayer01.h3m.prolog` | Dracon |
| _Armageddon's Blade_ | _Dragon Slayer_ | `ABvoDS2.wav` | `campaign.slayer.DragonSlayer02.h3m.prolog` | Dracon |
| _Armageddon's Blade_ | _Dragon Slayer_ | `ABvoDS3.wav` | `campaign.slayer.DragonSlayer03.h3m.prolog` | Dracon |
| _Armageddon's Blade_ | _Dragon Slayer_ | `ABvoDS4.wav` | `campaign.slayer.DragonSlayer04.h3m.prolog` | Dracon |
| _Armageddon's Blade_ | _Dragon Slayer_ | `ABvoDS5.wav` | `campaign.slayer.DragonSlayer04.h3m.epilog` | Dracon |
| _Armageddon's Blade_ | _Festival of life_ | `ABvoFL1.wav` | `campaign.festival.Festival of life 1.h3m.prolog` | Kilgor |
| _Armageddon's Blade_ | _Festival of life_ | `ABvoFL2.wav` | `campaign.festival.Festival of life 2.h3m.prolog` | Kilgor |
| _Armageddon's Blade_ | _Festival of life_ | `ABvoFL3.wav` | `campaign.festival.Festival of Life 3.h3m.prolog` | Kilgor |
| _Armageddon's Blade_ | _Festival of life_ | `ABvoFL4.wav` | `campaign.festival.Festival of life 4.h3m.prolog` | Kilgor |
| _Armageddon's Blade_ | _Festival of life_ | `ABvoFL5.wav` | `campaign.festival.Festival of life 4.h3m.epilog` | Kilgor |
| _Armageddon's Blade_ | _Playing with Fire_ | `ABvoPF1.wav` | `campaign.fire.Adrienne1.h3m.prolog` | Adrienne |
| _Armageddon's Blade_ | _Playing with Fire_ | `ABvoPF2.wav` | `campaign.fire.Adrienne2.h3m.prolog` | Adrienne |
| _Armageddon's Blade_ | _Playing with Fire_ | `ABvoPF3.wav` | `campaign.fire.Adrienne3.h3m.prolog` | Adrienne |
| _Armageddon's Blade_ | _Playing with Fire_ | `ABvoPF4.wav` | `campaign.fire.Adrienne3.h3m.epilog` | Adrienne |
| _Armageddon's Blade_ | _Foolhardy Waywardness_ | `ABvoFW1.wav` | `campaign.fool.Secret 1 - Lost at Sea.h3m.prolog` | Sir Christian |
| _Armageddon's Blade_ | _Foolhardy Waywardness_ | `ABvoFW2.wav` | `campaign.fool.Secret 2 - Their End Of the Bargain.h3m.prolog` | Sir Christian |
| _Armageddon's Blade_ | _Foolhardy Waywardness_ | `ABvoFW3.wav` | `campaign.fool.Secret 3 - Here There Be Pirates.h3m.prolog` | Sir Christian |
| _Armageddon's Blade_ | _Foolhardy Waywardness_ | `ABvoFW4.wav` | `campaign.fool.Secret 4 - Hurry Up and Wait.h3m.prolog` | Sir Christian |
| _Armageddon's Blade_ | _Foolhardy Waywardness_ | `ABvoFW5.wav` | `campaign.fool.Secret 4 - Hurry Up and Wait.h3m.epilog` | Sir Christian |
| _Shadow Of the Death_ | _New Beginning_ | `H3x2NBa.wav` | `campaign.gem.Gem2.h3m.prolog` | Gem |
| _Shadow Of the Death_ | _New Beginning_ | `H3x2NBb.wav` | `campaign.gem.Gem1.h3m.prolog` | Gem |
| _Shadow Of the Death_ | _New Beginning_ | `H3x2NBc.wav` | `campaign.gem.Gem3.h3m.prolog` | Gem |
| _Shadow Of the Death_ | _New Beginning_ | `H3x2NBd.wav` | `campaign.gem.Gem4.h3m.prolog` | Gem |
| _Shadow Of the Death_ | _New Beginning_ | `H3x2NBe.wav` | `campaign.gem.Gem4.h3m.epilog` | Gem |
| _Shadow Of the Death_ | _Elixir of Life_ | `H3x2ELa.wav` | `campaign.gelu.gelu1.h3m.prolog` | Gelu's mentor |
| _Shadow Of the Death_ | _Elixir of Life_ | `H3x2ELb.wav` | `campaign.gelu.gelu2.h3m.prolog` | Gelu's mentor |
| _Shadow Of the Death_ | _Elixir of Life_ | `H3x2Elc.wav` | `campaign.gelu.gelu3.h3m.prolog` | Gelu's mentor |
| _Shadow Of the Death_ | _Elixir of Life_ | `H3x2ELd.wav` | `campaign.gelu.gelu4.h3m.prolog` | Gelu's mentor |
| _Shadow Of the Death_ | _Elixir of Life_ | `H3x2ELe.wav` | `campaign.gelu.gelu4.h3m.epilog` | Gelu |
| _Shadow Of the Death_ | _Hack and Slash_ | `H3x2HSa.wav` | `campaign.crag.Has01.h3m.prolog` | CRAG Hack |
| _Shadow Of the Death_ | _Hack and Slash_ | `H3x2HSb.wav` | `campaign.crag.Has02.h3m.prolog` | CRAG Hack |
| _Shadow Of the Death_ | _Hack and Slash_ | `H3x2HSc.wav` | `campaign.crag.Has03.h3m.prolog` | CRAG Hack |
| _Shadow Of the Death_ | _Hack and Slash_ | `H3x2HSd.wav` | `campaign.crag.Has04.h3m.prolog` | CRAG Hack |
| _Shadow Of the Death_ | _Hack and Slash_ | `H3x2HSe.wav` | `campaign.crag.Has04.h3m.epilog` | CRAG Hack |
| _Shadow Of the Death_ | _Rise of the Necromancer_ | `H3x2RNa.wav` | `campaign.sandro.Sandro A.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Rise of the Necromancer_ | `H3x2RNb.wav` | `campaign.sandro.Sandro B.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Rise of the Necromancer_ | `H3x2RNc.wav` | `campaign.sandro.Sandro C.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Rise of the Necromancer_ | `H3x2RNd.wav` | `campaign.sandro.Sandro D.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Rise of the Necromancer_ | `H3x2RNe.wav` | `campaign.sandro.Sandro D.h3m.epilog` | Sandro |
| _Shadow Of the Death_ | _Birth of a Barbarian_ | `H3x2BBa.wav` | `campaign.yog.Yog A.h3m.prolog` | Yog |
| _Shadow Of the Death_ | _Birth of a Barbarian_ | `H3x2BBb.wav` | `campaign.yog.Yog B.h3m.prolog` | Yog |
| _Shadow Of the Death_ | _Birth of a Barbarian_ | `H3x2BBc.wav` | `campaign.yog.Yog C.h3m.prolog` | Yog |
| _Shadow Of the Death_ | _Birth of a Barbarian_ | `H3x2BBd.wav` | `campaign.yog.Yog D.h3m.prolog` | Yog |
| _Shadow Of the Death_ | _Birth of a Barbarian_ | `H3x2BBe.wav` | `campaign.yog.Yog E.h3m.prolog` | Yog |
| _Shadow Of the Death_ | _Birth of a Barbarian_ | `H3x2BBf.wav` | `campaign.yog.Yog E.h3m.epilog` | Yog |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAa.wav` | `campaign.final.Final A.h3m.prolog` | Yog |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAb.wav` | `campaign.final.Final B.h3m.prolog` | CRAG Hack |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAc.wav` | `campaign.final.Final C.h3m.prolog` | Gelu |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAd.wav` | `campaign.final.Final D.h3m.prolog` | Gem |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAe.wav` | `campaign.final.Final E.h3m.prolog` | Yog |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAf.wav` | `campaign.final.Final F.h3m.prolog` | Gelu |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAg.wav` | `campaign.final.Final G.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAh.wav` | `campaign.final.Final H.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAi.wav` | `campaign.final.Final I.h3m.prolog` | Gelu |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAj.wav` | `campaign.final.Final J .h3m.prolog` | Yog |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAk.wav` | `campaign.final.Final K.h3m.prolog` | Gem |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAl.wav` | `campaign.final.Final L.h3m.prolog` | Gem |
| _Shadow Of the Death_ | _Unholy Alliance_ | `H3x2UAm.wav` | `campaign.final.Final L.h3m.epilog` | Yog |
| _Shadow Of the Death_ | _Specter of Power_ | `H3x2SPa.wav` | `campaign.secret.Secret A.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Specter of Power_ | `H3x2SPb.wav` | `campaign.secret.Secret B.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Specter of Power_ | `H3x2SPc.wav` | `campaign.secret.Secret C.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Specter of Power_ | `H3x2SPd.wav` | `campaign.secret.Secret D.h3m.prolog` | Sandro |
| _Shadow Of the Death_ | _Specter of Power_ | `H3x2SPe.wav` | `campaign.secret.Secret D.h3m.epilog` | Sandro |
| _Horn of the Abyss_ | _Jolly Roger_ | `ROGER1.wav` | `campaign.h1roger.0101.h3m.prolog` | Jolly Roger's narrator |
| _Horn of the Abyss_ | _Jolly Roger_ | `ROGER2.wav` | `campaign.h1roger.0102.h3m.prolog` | Jolly Roger's narrator |
| _Horn of the Abyss_ | _Jolly Roger_ | `ROGER3.wav` | `campaign.h1roger.0103.h3m.prolog` | Jolly Roger's narrator |
| _Horn of the Abyss_ | _Jolly Roger_ | `ROGER4.wav` | `campaign.h1roger.0103.h3m.epilog` | Jolly Roger's narrator |
| _Horn of the Abyss_ | _Terror on the Sea_ | `TERROR1.wav` | `campaign.h2terror.0201.h3m.prolog` | Terror on the Sea's narrator |
| _Horn of the Abyss_ | _Terror on the Sea_ | `TERROR2.wav` | `campaign.h2terror.0202.h3m.prolog` | Terror on the Sea's narrator |
| _Horn of the Abyss_ | _Terror on the Sea_ | `TERROR3.wav` | `campaign.h2terror.0203.h3m.prolog` | Terror on the Sea's narrator |
| _Horn of the Abyss_ | _Terror on the Sea_ | `TERROR4.wav` | `campaign.h2terror.0204.h3m.prolog` | Terror on the Sea's narrator |
| _Horn of the Abyss_ | _Terror on the Sea_ | `TERROR5.wav` | `campaign.h2terror.0205.h3m.prolog` | Terror on the Sea's narrator |
| _Horn of the Abyss_ | _Terror on the Sea_ | `TERROR6.wav` | `campaign.h2terror.0206.h3m.prolog` | Terror on the Sea's narrator |
| _Horn of the Abyss_ | _Terror on the Sea_ | `TERROR7.wav` | `campaign.h2terror.0206.h3m.epilog` | Terror on the Sea's narrator |
| _Horn of the Abyss_ | _Horn of the Abyss_ | `HORN1.wav` | `campaign.h3horn.0301.h3m.prolog` | Horn of the Abyss's narrator |
| _Horn of the Abyss_ | _Horn of the Abyss_ | `HORN2.wav` | `campaign.h3horn.0302.h3m.prolog` | Horn of the Abyss's narrator |
| _Horn of the Abyss_ | _Horn of the Abyss_ | `HORN3.wav` | `campaign.h3horn.0303.h3m.prolog` | Horn of the Abyss's narrator |
| _Horn of the Abyss_ | _Horn of the Abyss_ | `HORN4.wav` | `campaign.h3horn.0304.h3m.prolog` | Horn of the Abyss's narrator |
| _Horn of the Abyss_ | _Horn of the Abyss_ | `HORN5.wav` | `campaign.h3horn.0304.h3m.epilog` | Horn of the Abyss's narrator |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT01.wav` | `campaign.h4fact.0401.h3m.prolog` | Henrietta |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT02.wav` | `campaign.h4fact.0401.h3m.epilog` | Henrietta |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT03.wav` | `campaign.h4fact.0402.h3m.prolog` | Henrietta |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT04.wav` | `campaign.h4fact.0402.h3m.epilog` | Henrietta |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT05.wav` | `campaign.h4fact.0403.h3m.prolog` | Henrietta |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT06.wav` | `campaign.h4fact.0403.h3m.epilog` | Henrietta |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT07.wav` | `campaign.h4fact.0404.h3m.prolog` | Frederick |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT08.wav` | `campaign.h4fact.0404.h3m.epilog` | Frederick |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT09.wav` | `campaign.h4fact.0405.h3m.prolog` | Frederick |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT10.wav` | `campaign.h4fact.0405.h3m.prolog2` | Frederick |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT11.wav` | `campaign.h4fact.0405.h3m.epilog` | Frederick |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT12.wav` | `campaign.h4fact.0405.h3m.epilog2` | Frederick |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT13.wav` | `campaign.h4fact.0406.h3m.prolog` | Wynona |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT14.wav` | `campaign.h4fact.0406.h3m.epilog` | Wynona |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT15.wav` | `campaign.h4fact.0407.h3m.prolog` | Frederick |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT16.wav` | `campaign.h4fact.0408.h3m.epilog` | Henrietta |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT17.wav` | `campaign.h4fact.0408.h3m.prolog` | Henrietta |
| _Horn of the Abyss_ | _Forged in Fire_ | `FACT18.wav` | `campaign.h4fact.0408.h3m.epilog` | Henrietta |
| _Horn of the Abyss_ | _All In_ | `ALLIN1.wav` | `campaign.h4fact.0501.h3m.prolog` | Dargham LLYWELLYN |
| _Horn of the Abyss_ | _All In_ | `ALLIN2.wav` | `campaign.h4fact.0502.h3m.prolog` | Dargham LLYWELLYN |
| _Horn of the Abyss_ | _All In_ | `ALLIN3.wav` | `campaign.h4fact.0503.h3m.prolog` | Dargham LLYWELLYN |
| _Horn of the Abyss_ | _All In_ | `ALLIN4.wav` | `campaign.h4fact.0504.h3m.prolog` | Dargham LLYWELLYN |
| _Horn of the Abyss_ | _All In_ | `ALLIN5.wav` | `campaign.h4fact.0505.h3m.prolog` | Dargham LLYWELLYN |
| _Horn of the Abyss_ | _All In_ | `ALLIN6.wav` | `campaign.h5allin.0505.h3m.epilog` | Dargham LLYWELLYN |
