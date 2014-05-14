# jquery.first3

Very simple plugin to wrap a number of first words of an element in another.

# Usage
  By default the first 3 words are wrapped in a `<span>`

    $('.someSelected').first3();

## Options

    elem: "<span>"
    cls:  null
    words: 3

## Examples

  Wraps first 3 words in a `<span>` without a css class

    $("p").first3();

  Wraps first 5 words in a `<div>` without a css class

    $("p").first3({
      elem: "<div>",
      words: 5
    });

  Wraps first 10 words in a `<h1>` with css class `someClass`

      $("p").first3({
      elem: "<h1>",
      cls: "someClass"
      words: 10
    });
