enum LegalContent {
    static let effectiveDate = "August 22, 2026"
    // (Note: to also keep your name off the App Store *listing*, you need an Apple Developer Organization
    // account — individual accounts display the person's legal name as the seller.)
    static let developerName = "Ascent"
    static let contactEmail = "brokearis@gmail.com"
    static let jurisdiction = "[State/Country]"

    static let terms: [LegalSection] = [
        LegalSection(heading: "1. Agreement to These Terms",
                     body: "These Terms of Service (the \u{201C}Terms\u{201D}) are a binding agreement between you and \(developerName) (\u{201C}we,\u{201D} \u{201C}us\u{201D}) governing your use of the Ascent mobile application (the \u{201C}App\u{201D}). By downloading, accessing, or using the App, you agree to these Terms. If you do not agree, do not use the App."),
        LegalSection(heading: "2. Eligibility",
                     body: "You must be at least 13 years old (or the minimum age of digital consent in your country) to use the App. If you are under the age of majority, you may use the App only with the involvement of a parent or legal guardian."),
        LegalSection(heading: "3. License",
                     body: "Subject to these Terms, we grant you a personal, limited, non-exclusive, non-transferable, revocable license to use the App on Apple devices you own or control, solely for your personal, non-commercial use. You may not copy, modify, reverse engineer, distribute, or create derivative works from the App except as permitted by law."),
        LegalSection(heading: "4. Ascent Limitless Subscription",
                     body: "The App offers an auto-renewable subscription (\u{201C}Ascent Limitless\u{201D}) that unlocks unlimited analyses and additional customization. Pricing and subscription length are shown on the purchase screen. Payment is charged to your Apple ID account at confirmation of purchase."),
        LegalSection(heading: "5. Auto-Renewal, Billing, and Cancellation",
                     body: "Your subscription automatically renews for the same period unless you cancel it at least 24 hours before the end of the current period. Your Apple ID is charged for renewal within 24 hours before the current period ends. You can manage or cancel your subscription in your device Settings under your Apple ID > Subscriptions. Deleting the App does not cancel your subscription."),
        LegalSection(heading: "6. Refunds",
                     body: "All purchases are processed by Apple and are subject to Apple\u{2019}s terms. We do not directly control billing and generally cannot issue refunds; refund requests are handled by Apple through your Apple ID account."),
        LegalSection(heading: "7. Safety and No Professional Advice",
                     body: "Climbing is an inherently dangerous activity that you undertake at your own risk. The App provides automated movement estimates and scores for informational and entertainment purposes only. It is not coaching, medical, physical-therapy, or safety advice, and it may be inaccurate. Always use proper technique, equipment, and supervision, and consult qualified professionals for training or health decisions."),
        LegalSection(heading: "8. Your Content",
                     body: "You retain ownership of the videos you analyze. Videos are processed on your device to generate movement data. You are responsible for having the rights to any video you use and for the privacy of anyone appearing in it. You grant us a limited license to process anonymized movement metrics as described in our Privacy Policy to operate and improve the App."),
        LegalSection(heading: "9. Acceptable Use",
                     body: "You agree not to use the App to violate any law, infringe others\u{2019} rights, upload unlawful content, interfere with the App\u{2019}s operation, or attempt to access it in an unauthorized way."),
        LegalSection(heading: "10. Disclaimers",
                     body: "The App is provided \u{201C}as is\u{201D} and \u{201C}as available\u{201D} without warranties of any kind, whether express or implied, including merchantability, fitness for a particular purpose, and non-infringement. We do not warrant that the App will be uninterrupted, error-free, or accurate."),
        LegalSection(heading: "11. Limitation of Liability",
                     body: "To the maximum extent permitted by law, \(developerName) will not be liable for any indirect, incidental, special, consequential, or punitive damages, or for any loss of data, profits, or goodwill, arising from your use of the App. Our total liability for any claim will not exceed the amount you paid us in the 12 months before the claim."),
        LegalSection(heading: "12. Changes",
                     body: "We may update the App and these Terms from time to time. Material changes will be reflected by updating the effective date above. Your continued use of the App after changes take effect constitutes acceptance of the revised Terms."),
        LegalSection(heading: "13. Termination",
                     body: "We may suspend or terminate your access to the App if you violate these Terms. Upon termination, the license granted to you ends and you must stop using the App."),
        LegalSection(heading: "14. Governing Law",
                     body: "These Terms are governed by the laws of \(jurisdiction), without regard to its conflict-of-laws rules, except where local consumer-protection law requires otherwise."),
        LegalSection(heading: "15. Contact",
                     body: "Questions about these Terms can be sent to \(contactEmail).")
    ]
