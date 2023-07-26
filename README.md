# NegPiP - Negative Prompt in Prompt
Extension for Stable Diffusion web-ui enables negative prompt in prompt / 負の効果を持つプロンプトを使えるようになります  
日本語は下の方。

# Summary
This extension enhances the stable diffusion web-ui prompts and cross-attention, allowing for the use of prompts with negative effects within regular prompts and prompts with positive effects within negative prompts. Typically, unwanted elements are placed in negative prompts, but negative prompts may not always have a significant impact in calculations. With this extension, it becomes possible to use negative prompts with effects comparable to regular prompts. This enables stronger effects even for words that might have collapsed when their values were increased too much in negative prompts before, by incorporating negative effects into the prompts.

# Instructions
By checking the "Active" box, it will become effective. In the prompt input screen, entering a negative value like (word:-1) will give it a negative effect. It also works with negative prompts, in which case it will have a positive effect.

# 概要
この拡張は、stable diffusion web-uiのプロンプトおよびクロスアテンションを拡張して、負の効果を持つプロンプトをプロンプト内で、正の効果を持つプロンプトをネガティブプロンプト内で使用できるようにします。通常、描きたくないものはネガティブプロンプトに書かれますが、ネガティブプロンプトの計算上、あまり効果が現れないことがあります。この拡張では、プロンプトと同程度の効果を持つ負のプロンプトを使用できるようにします。これにより、以前はネガティブプロンプトに置いて値を大きくしすぎて崩壊していたような単語でも、プロンプトに負の効果を持たせることができ、より強い効果が期待できます。

# 使い方
Activeにチェックを入れることで有効になります。プロンプト入力画面において (word:-1)のようにマイナスの値を入れることで負の効果を持つようになります。ネガティブプロンプトでも有効で、この場合は正の効果を持ちます。値は1より大きな値を入力しないと効果が現れない場合があります。
