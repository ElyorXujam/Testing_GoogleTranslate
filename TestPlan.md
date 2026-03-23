# Test Plan: Google Translate Web Application

## 1. Objective
- Test Google Translate web application to verify correct functionality of text, file, image, and website translation, including voice input, and language switching. Validate perfomance, usability, and accurancy under normal usage conditions.

## 2. Scope
### In Scope:
- Text translation(short and long phrases, symbols, multi-paragraph)
- File translation (PDF, DOCX)
- Image translation
- Website translation
- Voice input
- Language switching and language detection
- User interface elements and settings(theme layout)
### Out of Scope:
- API testing
- Load/Stress testing beyond normal user usage
- Mobile app versions (desktop web only)

## 3. Test Strategy
- **Functional Testing:** Verify all input types, translation outputs, language switching, and UI controls
- **Exploratory Testing:** Test edge cases such as mixed-language text, unsupported characters, large inputs, emojis, and unusual symbols
- **Perfomance Testing:** Measuer response time for text, file , and website translation under normal network conditons.
- **Usability Testing:** Ensure UI in intuitive, feedback messages are clear and controls behave as expected

## 4. Test Scenarios
- **1. Text translation:** Translate English text to Uzbek (*Accurate Translation displayed within 3 seconds*)
- **2. File translation:** Upload PDF/DOCX file and translate (*All text is tranlated correctly, formatting preserved*)
- **3. Image translation:** Upload image with text (*Text recognized and translated accurately*)
- **4. Website translation:** Translate a URL (*Web page content translated correctly and fully rendered*)
- **5. Voice input:** Speak into microphone (*Spoken text recognized and translated accurantely*)
- **6. Language switching:** Change source target languages (*Translation updates correctly*)
- **7. Virtual keyboard:** Type using on-screen  keyboard (*Text input works as expected*)
- **8. Edge cases:** Mixed language, symbols, long paragrphs (*No errors or crashes; meaningful feedback if unsupported*)

## 6. Environment

- Browser: Chrome Version 146.0.7680.154 (Official Build) (64-bit)
- OS: Windows 11 Pro
- Internet: Stable connection > 50 Mbps
- Test Data: Sample text, PDF/DOCX files, images, URLs

## Timeline

- Test plan prepartion - 2 hours 
- Functional & Exploratory testing - 4 hours
- Performance testing - 0.5 hour
- Bug logging & Reporting  1 hours

## 9. Entry & Exit Criteria
### Entry Criteria:
- Test environment set up and accessible
- Test data prepared (text, files, images, urls)
- Application deployed and stable

### Exit Criteria:
- All test scenarios executed
- Bugs reported
- Test results documented