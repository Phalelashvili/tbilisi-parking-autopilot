# Privacy Policy — Parking Autopilot

_Last updated: 21 November 2026_

---

## English

**Parking Autopilot collects no personal data.** The only thing it sends us is crash reports
and diagnostic logs, and those carry no name, account, location or vehicle.

### What stays on your phone

| Data | Why | Where it lives |
| --- | --- | --- |
| Location | To detect that you parked, and that you returned to your car | On the device. Never transmitted |
| Motion & fitness | To tell driving apart from walking, so you aren't asked to park while on foot | On the device. Never transmitted |
| Settings, vehicle list, activity log | To run the app | On the device (app storage) |
| Your parking-service sign-in token | To stay signed in | iOS Keychain, on the device |

Parking places are matched to your location entirely on your phone, against a catalogue of
Tbilisi's parking places included in the app. No location lookup leaves the device.

### What is sent, and to whom

The app is a client for Tbilisi's municipal parking service (`parking.tbilisi.gov.ge`,
`api.municipal.gov.ge`), operated by the Tbilisi municipality. When you sign in and use it,
these go to that service, on your own account:

- your sign-in, through the service's own web login
- the parking place code and the vehicle, when a session starts
- the request to stop a session
- requests to read your balance, vehicles and parking history

That is the same data the official app or website sends for the same actions, and the
service's own privacy policy governs it. We receive none of it.

### Crash reports and diagnostics

When the app crashes or something fails, a report goes to Sentry (Functional Software, Inc.),
the service we use to find and fix bugs. Reports are stored in Sentry's EU data region.

A report contains the app version, device model, iOS version, the error, which parking-service
request failed (with ids removed), and the names of recent app events, such as "session
started".

It never contains your location, parking place codes, vehicle plates, name, phone number or
sign-in token. Reports are not linked to you; a random identifier only groups reports from the
same installation. They are used for nothing but fixing the app, and Sentry deletes them
automatically after its retention period.

### What the app does not do

- No analytics, no advertising, no tracking
- No third-party SDKs other than Sentry, for the crash reports above
- No data is sold, shared or used for profiling
- No account is created with us — there is no account with us to create

### Permissions you can refuse

Location, notifications and motion are each asked for separately and explained in the app.
Refusing any of them leaves the rest working; without location, parking is started and
stopped manually. You can change them any time in iOS Settings.

### Children

The app is not directed at children and collects no personal data from anyone.

### Deleting your data

Deleting the app removes everything it stored on your phone, including the sign-in token.
Data held by the parking service is theirs — contact them to have it removed. Crash reports
aren't linked to you, so they can't be picked out by person; they expire on their own.

### Contact

`phalelashvili@protonmail.com`

---

## ქართული

**Parking Autopilot არ აგროვებს პერსონალურ მონაცემებს.** ჩვენამდე მხოლოდ შეცდომების
ანგარიშები და დიაგნოსტიკური ჩანაწერები მოდის, რომლებიც არ შეიცავს სახელს, ანგარიშს,
მდებარეობას ან ავტომობილს.

### რა რჩება თქვენს ტელეფონში

| მონაცემი | რისთვის | სად ინახება |
| --- | --- | --- |
| მდებარეობა | რომ დადგინდეს, სად გააჩერეთ და როდის დაბრუნდით | მოწყობილობაზე. არსად არ იგზავნება |
| მოძრაობის მონაცემები | რომ განვასხვავოთ მანქანით მგზავრობა ფეხით სიარულისგან | მოწყობილობაზე. არსად არ იგზავნება |
| პარამეტრები, ავტომობილები, აქტივობის ჟურნალი | აპლიკაციის მუშაობისთვის | მოწყობილობაზე |
| პარკინგის სერვისში შესვლის ტოკენი | რომ დარჩეთ სისტემაში | iOS Keychain-ში, მოწყობილობაზე |

პარკირების ადგილი თქვენს მდებარეობას ემთხვევა უშუალოდ ტელეფონში, აპლიკაციაში ჩაშენებული
თბილისის პარკირების ადგილების კატალოგის მიხედვით. მდებარეობის შესახებ არცერთი მოთხოვნა
მოწყობილობას არ ტოვებს.

### რა იგზავნება და ვის

აპლიკაცია არის კლიენტი თბილისის მუნიციპალური პარკირების სერვისისთვის
(`parking.tbilisi.gov.ge`, `api.municipal.gov.ge`). შესვლის შემდეგ ამ სერვისს, თქვენივე
ანგარიშზე, ეგზავნება:

- ავტორიზაცია — სერვისის საკუთარი ვებ-გვერდის მეშვეობით
- პარკირების ადგილის კოდი და ავტომობილი — სესიის დაწყებისას
- სესიის შეწყვეტის მოთხოვნა
- ბალანსის, ავტომობილებისა და ისტორიის წაკითხვის მოთხოვნები

ეს იგივე მონაცემებია, რასაც ოფიციალური აპლიკაცია ან ვებ-გვერდი აგზავნის იმავე მოქმედებებზე,
და მათზე ვრცელდება სერვისის საკუთარი კონფიდენციალურობის პოლიტიკა. ჩვენ მათ არ ვიღებთ.

### შეცდომების ანგარიშები და დიაგნოსტიკა

როცა აპლიკაცია ავარიულად იხურება ან რამე ვერ სრულდება, ანგარიში იგზავნება Sentry-ში
(Functional Software, Inc.) — სერვისში, რომლითაც შეცდომებს ვპოულობთ და ვასწორებთ.
ანგარიშები ინახება Sentry-ის ევროკავშირის მონაცემთა რეგიონში.

ანგარიში შეიცავს აპლიკაციის ვერსიას, მოწყობილობის მოდელს, iOS-ის ვერსიას, შეცდომას,
პარკირების სერვისის რომელი მოთხოვნა ჩავარდა (იდენტიფიკატორების გარეშე) და აპლიკაციის
ბოლო მოვლენების სახელებს, მაგალითად „სესია დაიწყო“.

ის არასოდეს შეიცავს თქვენს მდებარეობას, საპარკინგე ადგილების კოდებს, ავტომობილის ნომრებს,
სახელს, ტელეფონის ნომერს ან შესვლის ტოკენს. ანგარიშები თქვენთან არ არის დაკავშირებული;
შემთხვევითი იდენტიფიკატორი მხოლოდ ერთი ინსტალაციის ანგარიშებს აჯგუფებს. ისინი მხოლოდ
აპლიკაციის გასასწორებლად გამოიყენება და Sentry მათ შენახვის ვადის გასვლისას თავად შლის.

### რას არ აკეთებს აპლიკაცია

- არანაირი ანალიტიკა, რეკლამა ან თვალყურის დევნება
- მესამე მხარის SDK არ გამოიყენება, გარდა Sentry-ისა — ზემოთ აღწერილი ანგარიშებისთვის
- მონაცემები არ იყიდება და არ ზიარდება
- ჩვენთან ანგარიში არ იქმნება

### ნებართვები, რომლებზეც უარის თქმა შეგიძლიათ

მდებარეობა, შეტყობინებები და მოძრაობა ცალ-ცალკე იკითხება და აპლიკაციაშივეა ახსნილი.
ნებისმიერზე უარის თქმის შემთხვევაში დანარჩენი მუშაობს; მდებარეობის გარეშე პარკინგი ხელით
იწყება და სრულდება. შეცვლა ნებისმიერ დროს შეგიძლიათ iOS-ის პარამეტრებში.

### ბავშვები

აპლიკაცია არ არის განკუთვნილი ბავშვებისთვის და არავისგან არ აგროვებს პერსონალურ მონაცემებს.

### მონაცემების წაშლა

აპლიკაციის წაშლა შლის ყველაფერს, რაც მან ტელეფონში შეინახა, შესვლის ტოკენის ჩათვლით.
პარკირების სერვისში დაცული მონაცემები მათია — წასაშლელად დაუკავშირდით მათ. შეცდომების
ანგარიშები თქვენთან დაკავშირებული არ არის, ამიტომ პიროვნების მიხედვით ვერ მოიძებნება;
ისინი ვადის გასვლისას თავად იშლება.

### კონტაქტი

`phalelashvili@protonmail.com`
