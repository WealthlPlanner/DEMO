<div class="section meeting-form" id="book-meeting">
    <h2>Book a Meeting</h2>
    <form action="mailto:preggie@preggiegovender.com" method="post" enctype="text/plain">
        <label for="name">Name:</label>
        <input type="text" id="name" name="Name" autocomplete="on:"given-name" required>

        <label for="surname">Surname:</label>
        <input type="text" id="surname" name="Surname" autocomplete"on"="family-name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="Email" autocomplete="on""email" required>

        <label for="contact">Contact Number:</label>
        <input type="tel" id="contact" name="Contact" autocomplete="on""tel" required>

        <label for="message">Additional Details (Optional):</label>
        <textarea id="message" name="Message" rows="4" autocomplete="on"></textarea>

        <button type="submit">Send Meeting Request</button>
    </form>
</div>
