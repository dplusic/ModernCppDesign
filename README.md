# ModernCppDesign
Study of "Modern C++ Design"

## Chapters

#### Foreword by Scott Meyers
##### Physical<>
* Codes
    * https://wandbox.org/permlink/c8ewOlhBqO0KnP40
    * https://wandbox.org/permlink/a5nH0EInhRCp73qi (using `constexpr`)
* Reference
    * http://se.ethz.ch/~meyer/publications/OTHERS/scott_meyers/dimensions.pdf
    * https://www.codeproject.com/Articles/447922/Application-of-Cplusplus-User-Defined-Literals-t
    * https://benjaminjurke.com/content/articles/2015/compile-time-numerical-unit-dimension-checking/

### Chapter 1
#### 1.4 The Benefit of Templates
##### Several problems
* Codes
    * https://wandbox.org/permlink/kXbzl7humO4e4p8e
* Reference
    * http://lukaswoodtli.github.io/modern_cpp_design.html#the-benefit-of-templates
    
#### 1.6 Enriched Policies
* :question: Is it possible to prevent missing to call `SetPrototype`?

#### 1.7 Destructors of Policy Classes
* :question: Is it possible to prevent unintended type casting?
* :question: Is it neccessary to inherit Policy Classes?
    
#### Reference
* https://www.slideshare.net/lactrious/policy-based-class-design


### Chapter 2

#### 2.1 Compile-Time Assertions
* :question: `error: invalid application of 'sizeof' to a function type`
    * https://wandbox.org/permlink/NBgMWthHfZMqAm03
* `reinterpret_cast` do check the case of losing precision.
* Codes
    * https://wandbox.org/permlink/HHNBgIx1RHXrBJU6

## Reference
* http://my.safaribooksonline.com/book/programming/cplusplus/0201704315
* https://github.com/LukasWoodtli/ModernCppDesign
