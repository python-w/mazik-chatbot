# mazik-chatbot
This React demo app serves as an interactive chatbot interface with dynamic responses, file uploads, and bot options presented in card format.

Key Functionalities:

**1. Message Handling**
   - State: Maintains `messages`, `input`, `files`, `botOptions`, and `showCompanyCard` as state variables.
   - User Input: Handles user messages and file uploads.
   - Bot Responses: Generates responses based on user input, including suggestions and options.

**2. Bot Response Logic**
   - Custom Responses: Responds to user inputs with predefined text or shows options (e.g., proposal requests).
   - Options Generation: Displays selectable options like “Record to Report” in bold text.
   - Company Card: Shows a company info card when specific keywords (like "proposal") are detected.

**3. File Uploads & Previews**
   - Allows users to upload files.
   - Displays previews of uploaded files with remove functionality.

**4. Bot Options as Cards**
   - Card Layout: Bot options are shown inside Material UI `Card` components.
   - Checkboxes: Users can select bot options, which triggers further responses or renders a company card.

**5. Styled Components**
   - Uses Material UI components like `Box`, `Typography`, `Card`, and `IconButton` for the layout.
   - Includes a custom `StyledInputBase` for the input field.

**6. File Upload and Input Handling**
   - Handles file selection via `input` elements.
   - Renders a list of attached files with preview and remove options.

**7. Icons & UI Elements**
   - Uses FontAwesome icons for styling elements like attachments and send buttons.
   - Material UI’s `Send` icon for the send button functionality.

Integration:
- BotOptions: Presents suggestions in bold.
- Company Info Card: Dynamically shows based on input.
- File Handling: Allows for multiple file uploads, previews, and removal.

