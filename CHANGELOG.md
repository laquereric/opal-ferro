# 0.10.1 - March 31, 2018

- Added documentation (using Yard)
- Modularized Ferro (breaking change), see below
- AJAX can now handle any type of request (not just get)

To upgrade from 0.10.0 to 0.10.1:

- replace FerroDocument with Ferro::Document
- replace FerroXhr with Ferro::Xhr
- replace FerroSequence with Ferro::Sequence
- replace FerroElementForm with Ferro::Form::Base
- replace FerroElementForm... with Ferro::Form::...
- replace FerroElementComponent with Ferro::Component::Base
- replace FerroElementComponent... with Ferro::Component::...
- replace FerroSearch with Ferro::Combo::Search
- replace FerroPullDown with Ferro::Combo::PullDown
- replace FerroElement... with Ferro::Element::...


# 0.10.0 - February 2, 2018

Initial version
