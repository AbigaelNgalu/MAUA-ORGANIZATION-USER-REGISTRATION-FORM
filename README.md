<form action="/submit-form" method="post">
    <fieldset>
        <legend>Contact Information</legend>
        <p>
            <label for="name">Name:</label>
            <input type="text" id="name" name="user_name" required>
        </p>
        <p>
            <label for="email">Email:</label>
            <input type="email" id="email" name="user_email" required>
        </p>
    </fieldset>

    <fieldset>
        <legend>Payment Details</legend>
        <p>
            <label for="card_type">Credit Card Type:</label>
            <select id="card_type" name="card_type">
                <option value="visa">Visa</option>
                <option value="mastercard">MasterCard</option>
            </select>
        </p>
        <p>
            <label for="card_number">Card Number:</label>
            <input type="text" id="card_number" name="card_number" pattern="[0-9]{16}" title="16-digit card number" required>
        </p>
    </fieldset>

    <p>
        <button type="submit">Submit Form</button>
    </p>
</form>
