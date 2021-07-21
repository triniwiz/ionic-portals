# Ionic Portals

<svg width="320" height="79" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M158 56.12c5.523 0 10-4.477 10-10s-4.477-10-10-10-10 4.477-10 10 4.477 10 10 10zm0 10c11.046 0 20-8.954 20-20s-8.954-20-20-20-20 8.954-20 20 8.954 20 20 20z" fill="#fff"></path><path d="M109.912 36.104V23.648h11.376c4.824 0 6.912 2.592 6.912 6.264s-2.088 6.192-6.912 6.192h-11.376zm0 9.648h11.376c11.88 0 17.424-6.912 17.424-15.84S133.6 14 121.288 14H99.4v51.12h10.512V45.752zM202.74 27.104s-.864-.072-1.224-.072c-6.408 0-9.288 3.024-10.656 5.256v-4.896h-9.432V65.12h10.224V46.328c0-6.912 3.096-9.864 9.072-9.864.936 0 2.016.216 2.016.216v-9.576zM215.647 35.456h7.544v-8.064h-7.544v-9.36h-10.224V65.12h10.224V35.456zM252.552 27.392V32c-2.376-3.456-6.624-5.472-11.952-5.472-10.944 0-17.352 8.784-17.352 19.728s6.408 19.728 17.352 19.728c5.328 0 9.576-2.016 11.952-5.472v4.608h9.432V27.392h-9.432zm-.504 18.864c0 6.12-3.6 10.728-9.288 10.728-5.688 0-9.288-4.608-9.288-10.728s3.6-10.728 9.288-10.728c5.688 0 9.288 4.608 9.288 10.728zM277.391 65.12V14h-10.224v51.12h10.224zM297.016 65.984c10.224 0 15.984-5.328 15.984-12.096 0-15.48-20.88-9.144-20.88-15.48 0-2.088 1.872-3.672 5.184-3.672 3.672 0 5.472 2.16 5.688 4.536h9.864c-.288-5.544-4.176-12.744-15.48-12.744-9.288 0-15.12 5.616-15.12 12.456 0 14.976 20.952 9 20.952 15.336 0 2.088-2.016 3.456-5.904 3.456-4.248 0-6.12-2.376-6.264-4.896h-10.368c.504 7.056 4.536 13.104 16.344 13.104z" fill="#fff"></path><path d="M9.36 40c0-16.37 13.27-29.64 29.64-29.64 6.59 0 12.674 2.147 17.597 5.786a11.172 11.172 0 017.096-6.334A38.854 38.854 0 0039 1C17.46 1 0 18.46 0 40s17.46 39 39 39 39-17.46 39-39c0-4.508-.767-8.844-2.179-12.881a11.128 11.128 0 01-8.379 4.508A29.649 29.649 0 0168.64 40c0 16.37-13.27 29.64-29.64 29.64S9.36 56.37 9.36 40z" fill="url(#logo_svg__paint0_angular)"></path><g opacity="0.3" filter="url(#logo_svg__filter0_d)"><path d="M77.198 32.098a38.722 38.722 0 00-1.377-4.98 11.128 11.128 0 01-8.379 4.509c.551 1.875.922 3.83 1.092 5.844a12.186 12.186 0 008.664-5.373z" fill="#000"></path></g><path d="M39 57.063c9.401 0 17.063-7.647 17.063-17.063 0-9.401-7.647-17.063-17.063-17.063-9.416 0-17.063 7.662-17.063 17.063S29.6 57.063 39 57.063zM64.594 25.375a8.531 8.531 0 100-17.062 8.531 8.531 0 000 17.062z" fill="#fff"></path><defs><radialGradient id="logo_svg__paint0_angular" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="matrix(27.78743 -10.2375 10.37875 28.17084 39 40)"><stop stop-color="#fff" stop-opacity="0.4"></stop><stop offset="0.109" stop-color="#fff"></stop><stop offset="1" stop-color="#fff"></stop></radialGradient><filter id="logo_svg__filter0_d" x="63.442" y="27.119" width="17.756" height="18.352" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB"><feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood><feColorMatrix in="SourceAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"></feColorMatrix><feOffset dy="4"></feOffset><feGaussianBlur stdDeviation="2"></feGaussianBlur><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"></feColorMatrix><feBlend in2="BackgroundImageFix" result="effect1_dropShadow"></feBlend><feBlend in="SourceGraphic" in2="effect1_dropShadow" result="shape"></feBlend></filter></defs></svg>

Ionic Portals are native Android and iOS libraries used to embed Capacitor Webviews and Plugins into an existing native application.

## Getting Started

To get started with both projects, you can open up corresponding `PortalsTestApp` project in XCode or Android Studio.

### iOS

In iOS, you can open `ios/IonicPortals.xcworkspace` to open the test app with the `IonicPortals.xcodeproj` also loaded. The `IonicPortals` library will already be linked to the test app project and can be developed/built independantly of the test app.

### Android

In Android, you can open the `android/PortalsTestApp` folder and gradle should recognize that `android/IonicPortals` is a dependency of the project. This is done by linking the project in the `android/PortalsTestApp/settings.gradle` and including it in the dependency of the test app itself in `android/PortalsTestApp/app/build.gradle`.
