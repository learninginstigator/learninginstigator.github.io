<section id="user-input">
    <!--- This is the main user input section a form tag wraps the inputs we want to collect -->
    <form method="get">
        <div>
            <!-- This is a single input, it has a label and a input field for the user to enter information into. The name signifies the variable the input will be stored in -->
            <label for="adjective2">Adjective</label>
            <input type="text" name="adjective2" placeholder="adjective" />
        </div>
        <!-- Button for the user to click when submiting the form -->
        <input type="submit" />
    </form>
</section>

 
<!-- The madlib we will populate -->
<section id="madlib">
    <!-- we wrap the mad lib in a paragraph tag, inside of this we will need something to place the text into that the user submits. I am using a span because it displays on the page inline instead of something that would cause a linebreak to happen, such as another p tag or div.  The id is a tag we can use to specify which field this is, I am naming it the same as the name on the form input to keep things simple, it could be anything as long as it is unique. -->
    <p>I said <span id="adjective1"></span></p>

    <p>
<p>THE POWER OF THE FORCE
The Force is a mystical, <span id="adjective2"></span> power. As Jedi Master Obi-Wan Kenobi once said, “The Force is an energy field, created by all living (PLURAL NOUN), that surrounds us, penetrates us, and binds the (NOUN).” Using the power of the Force, a Jedi can do many (ADJECTIVE) things, like using the Force to exercise (PART OF THE BODY) control over (ADJECTIVE)-minded (PLURAL NOUN). A Jedi can also use the Force to move objects with their (PART OF THE BODY). It doesn’t matter how (ADJECTIVE) these objects are; it only matters how (ADVERB) the Jedi believes in the Force. Most importantly, the Force teaches a Jedi to rely on their feelings. As Obi-Wan Kenobi told his student Luke (NOUN)-Walker: “Your (PART OF THE BODY - PLURAL) can deceive you. Don’t trust them.” Instead, a Jedi should (ADVERB) trust the Force.

A Mad Lib
(from the ‘Star Wars Mad Libs’ book by Roger Price and Leonard Stern)

</section>

<!-- We will be putting code inside of script to handle the logic of how to handle the madlib population -->
<script>

</script>