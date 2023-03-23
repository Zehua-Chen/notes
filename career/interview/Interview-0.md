面试

作为在微软工作的Tech Lead，我参加过大大小小几十次面试。这里我希望从面试官的角度，给大家分享一下面试官喜欢和不喜欢的candidate的特征，并且给出实用的建议。

面试官不喜欢的面试者，有这几种特征：

第一，交流沟通不自信：很多面试者（尤其newgrads）我普遍感觉很容易在面试中表现得不自信，主要体现在 说话小心翼翼，或者是当面试官稍微质疑一下，就马上推翻自己的想法；这是对我来说亮红灯的情况，说明你不够有主见，然后算法基础也不是很牢固。

面对自己不会的算法题或者找不到最优解，很多时候大家就懵逼了，整个面试就会因此陷入沉默。其实大可不必，只要不卑不亢地把你知道的，和不知道的，有逻辑地讲出来，并且积极向面试官要hints，也是能展现你的优势的。我就给过一些没做出来题的同学hire的suggestion， 因为他们思维过程很好。

第二，用套路的痕迹比较重，主要体现在：

刚看完题不怎么思考，既没有问clarify的问题，也没有列举example, 就直接快准狠地把main question的答案写完了，但是对followup question怎么都想不出来，甚至给了明显的hint也没有进展。

生搬硬套算法：有时候是一道很简单的array就可以解决的题目, 但是candidate非要用graph来解决，但是我问为什么用这个数据结构，对方却答不出来，这就是生搬硬套了

还有的同学，明明知道了最好的solution，但是会故意先用暴力解决方法，但是优化的过程是断层的，
直接跳到最优解, 这其实就没有给面试官机会来引导你思考了，是减分的

第三个特征，太沉浸在自己的世界，不沟通：

很多咱们国人小伙伴，沟通是普遍偏少的，面试算法的时候更像是在自己写考卷，也不问导师要hints，也不说自己的思维过程。这里我想强调：虽然代码是很重要但是有效地沟通也很重要，面试算法很多时候是看你解决问题的能力，如果不把你的思维说出来，这点就没法考察了

那么，下面我来讲下自己很喜欢的candidate的特征：
第一，思路清晰相比直接给出答案的人，面试官会更喜欢。其实面试官不是想你把答案写出来而已，我们更看重how you get there. 而可以把这个过程讲清楚的人，往往也是在工作中能力会比较强的，也可以和team更好地work together。

第二，代码清晰简洁可读性强。这是一个可以训练的过程，在自己写完答案pass之后也要花一定的时间来优化自己的代码结构，看看别人写的代码怎么写的，比如用适当的helper function可以很好的抽象一些逻辑，加一些适当的comment，但是也要避免过度抽象的python的方法，这会让读起来很费劲

第三，主动提出不错的corner case，这个体现了你的思维缜密，对技术岗位是很重要的！

第四，注重testing, 写完之后，不要直接和面试官说你写完了，可以分析好时间和空间复杂度，并且向面试官建议你想跑1--2个例子，来验证自己的solution是否work。这是非常加分的