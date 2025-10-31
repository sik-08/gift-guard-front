[ui기능만.zip](https://github.com/user-attachments/files/23249099/ui.zip)



빌드 가드 추가한 부분 혹시 몰라 재작성


    // ⭐⭐ 여기를 주목하세요: 확장 아이콘 세트 (CameraAlt 포함)를 수동으로 추가했습니다.
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
