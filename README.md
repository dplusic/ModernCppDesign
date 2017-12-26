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
    * https://wandbox.org/permlink/gBoOuXovnIdkULnQ
* Reference
    * http://en.cppreference.com/w/cpp/language/static_assert

#### 2.4 Mapping Integral Constants to Types
* Codes
    * https://wandbox.org/permlink/v4sFH6NWrZEeEm8Y (using `constexpr` instead of `enum`)
    * https://wandbox.org/permlink/mQG2JTPvXtBcLhsy (`cannot specialize a member of an unspecialized template`)

#### 2.6 Type Selection
* Reference
    * http://en.cppreference.com/w/cpp/types/conditional

#### 2.7 Detecting Convertibility and Inheritance at Compile Time
* Reference
    * http://en.cppreference.com/w/cpp/types/is_convertible
    * http://en.cppreference.com/w/cpp/types/is_base_of
    * http://en.cppreference.com/w/cpp/language/decltype
    
#### 2.10 Type Traits
* Reference
    * https://sourceforge.net/p/loki-lib/code/HEAD/tree/trunk/include/loki/TypeTraits.h

## Reference
* http://my.safaribooksonline.com/book/programming/cplusplus/0201704315
* https://github.com/LukasWoodtli/ModernCppDesign
