# Update-App-for-google

Con esta nueva funcionalidad que brinda google podras tener actualizada tu app de manera tanto obligatoria(INMEDIATA) como de manera opcional(FLEXIBLE), con esto evitando problema con tus usuarios en el tema de solucion de errores anteriores.  

- **Requisitos:**

        implementation 'com.google.android.play:core:1.7.3'

- **Pasos a seguir**
        
        
  Primero debemos declarar:
  
        private val MY_REQUEST_CODE = 1
        private var installStateUpdatedListener: InstallStateUpdatedListener? = null
        private var mAppUpdateManager: AppUpdateManager? = null

        





