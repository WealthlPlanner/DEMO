<div class="section meeting-form" id="book-meeting">
    <h2>Book a Meeting</h2>
    <form action="mailto:preggie@preggiegovender.com" method="post" enctype="text/plain">
        <label for="name">Name:</label>
        <input type="text" id="name" name="Name" autocomplete="given-name" required>

        <label for="surname">Surname:</label>
        <input type="text" id="surname" name="Surname" autocomplete="family-name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="Email" autocomplete="email" required>

        <label for="contact">Contact Number:</label>
        <input type="tel" id="contact" name="Contact" autocomplete="tel" required>

        <label for="message">Additional Details (Optional):</label>
        <textarea id="message" name="Message" rows="4" autocomplete="off"></textarea>

        <button type="submit">Send Meeting Request</button>
    </form>
</div>
