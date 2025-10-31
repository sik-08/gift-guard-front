파일들 외에 기본 파일에 몇줄 추가된 내용

AndroidMainfest.xml 의  통신

<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools">

    빌드가드.app 

    dependencies {
    //  여기를 주목하세요: 확장 아이콘 세트 (CameraAlt 포함)를 수동으로 추가했습니다.
    implementation("androidx.compose.material:material-icons-extended")

    // Retrofit 및 JSON 변환 (Gson 또는 Moshi 등 선택)
    implementation("com.squareup.retrofit2:retrofit:2.9.0")
    implementation("com.squareup.retrofit2:converter-gson:2.9.0")

    // Kotlin Coroutines (비동기 처리)
    implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.3")

    // AndroidX Lifecycle (ViewModel 및 Coroutines 통합)
    implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:2.7.0")
    implementation("androidx.lifecycle:lifecycle-runtime-ktx:2.7.0")

    // Hilt, Koin 같은 DI 라이브러리를 사용하지 않는 경우 ViewModel 수동 생성 도구
    implementation("androidx.lifecycle:lifecycle-viewmodel-compose:2.7.0")

    // Retrofit 및 JSON 변환 (Gson 사용)
    implementation("com.squareup.retrofit2:retrofit:2.9.0")
    implementation("com.squareup.retrofit2:converter-gson:2.9.0")

// Kotlin Coroutines (비동기 처리)
    implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.3")

// AndroidX Lifecycle (ViewModel 및 Coroutines 통합)
    implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:2.7.0")
    implementation("androidx.lifecycle:lifecycle-runtime-ktx:2.7.0")

// Compose에서 ViewModel을 사용하기 위한 라이브러리
    implementation("androidx.lifecycle:lifecycle-viewmodel-compose:2.7.0")
    implementation("com.squareup.okhttp3:okhttp:4.12.0")
    implementation("com.squareup.okhttp3:logging-interceptor:4.12.0") // (선택 사항: 디버깅에 유용)

    
