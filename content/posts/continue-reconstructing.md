---
title: "LTNベースで再構築と採掘拡大"
date: 2019-01-09T10:02:10+09:00
draft: false
---

LTNが導入されたので、今まで作ってきたラインを解体し、LTN用のブロックで再構成する作業を進めている。

<!--more-->

今までは組み立て機1個だけとかだったのを複数並べられるように配置するなどして、今後の大規模化に備えている。

ようやく、赤回路が自動的に生成されるところまで来た。しかし、ここでSolder(ハンダ)が足りないという事態が深刻化してきた。Solderの原料となるTin(錫)が今の構成ではあんまり取れないのが原因。そのため、茶色石を出す、4つ目のGeode Processing Blockを構築しはじめた。

Geode Processsing Blockは、この [Factorio Prints](https://factorioprints.com/view/-LHyjlKZ0kD1I7TdqfaN) を使わせてもらっている。泥水からGeodeを作成し、任意の色の石を出せる。
かなり大規模だが、非常にバランスよく作られており無メンテでずっと動かし続けられる。これがなければここまで大きくできなかっただろうな、と思う。

なお、現時点で判明している問題がもうひとつあって、それは銀がまったく出ていないこと。Geode Processing Blockを構築する以前に構築したBlockから銀を出せていたので今はまだ間に合っているが、これから触媒および紫ビーカーの生成にいっぱい必要となるので、用意しておかなければならない。そのためには白色石が必要なので、さらに別のGeode Blockが必要となる。

こうなると今歩きで構築物資を届けているが、非常にたるくなるので線路を引き始めた。将来的には触媒に必要な石などもLTNに組み込んで組み立てブロックに組み込む予定。


{{< figure src="/images/2019-01-09-geode-processing.PNG" title="石がどんどん出てくるよ" class="center" >}}
