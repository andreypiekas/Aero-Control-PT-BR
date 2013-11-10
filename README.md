<resources>
    <string name="app_name">Aero Control</string>
    <string name="drawer_open">Abrir Gaveta de Notificação</string>
    <string name="drawer_close">Fechar Gaveta de Notificação</string>
    <string name="error_detected">Erro ?</string>
    <string name="cancel">Cancelar</string>
    <string name="save">Salvar</string>
    <string name="github">Github AeroControl</string>
    <string name="donation_blechdose">Faça uma doação para Blechdose</string>
    <string name="donation_quarx">Faça uma doação pra Quarx</string>
    <string name="default_values">Valores padrões</string>
    <string name="need_reboot">Isso ira necessitar de uma reinicialização.</string>
    <string name="unavailable">Indisponível</string>

    <!-- Entradas de gaveta de navegação padrão -->

    <string name="slider_overview">Visão geral</string>
    <string name="slider_cpu_settings">Desempenho de CPU</string>
    <string name="slider_gpu_settings">Controle de GPU</string>
    <string name="slider_memory_settings">Memory Tuning</string>
    <string name="slider_defy_parts">Defy Parts</string>
    <string name="slider_updater">Atualização</string>

    <string-array name="aero_array">
        <item>@string/slider_overview</item>
        <item>@string/slider_cpu_settings</item>
        <item>@string/slider_gpu_settings</item>
        <item>@string/slider_memory_settings</item>
        <item>@string/slider_defy_parts</item>
        <item>@string/slider_updater</item>
    </string-array>

    <!-- Visão geral -->

    <string name="kernel_version">Kernel:</string>
    <string name="current_cpu_speed">CPU Frequência:</string>
    <string name="current_gpu_speed">GPU Frequência:</string>
    <string name="current_governor">Governor:</string>
    <string name="current_io_governor">I/O-Scheduler:</string>
    <string name="available_memory">Memoria Total:</string>

    <string-array name="overview_array">
        <item>@string/kernel_version</item>
        <item>@string/current_cpu_speed</item>
        <item>@string/current_gpu_speed</item>
        <item>@string/current_governor</item>
        <item>@string/available_memory</item>
    </string-array>

    <!-- Action Overflow Menu -->

    <string name="about">Sobre</string>
    <string name="aero_settings">Configurações</string>

    <!-- Menu de preferências -->

    <string name="pref_appspecific">App especifico </string>
    <string name="pref_setatboot">Manter na inicialização</string>
    <string name="pref_setatboot_sum">Atenção: Isto irá definir as configurações no boot.</string>
    <string name="pref_updatepath">Updatelocation:</string>
    <string name="pref_updatepath_sum">Defina o seu caminho de atualização desejada.</string>
    <string name="pref_app_theme">App Theme</string>
    <string name="pref_app_theme_sum">Define o tema padrão do aplicativo.</string>

    <!-- Sobre -->
    <string name="about_dialog">Olá. Obrigado por usar este aplicativo. Meu nome é
                         Alexander Cristo (Blechd0se) e eu criei este App para se divertir e no meu tempo livre.
                         Ele é também Open Source, assim você pode pegar o código fonte e modificá-lo como quiser.
                         Se você quiser, você pode doar para Quarx por sua incrível rom ou para mim.
                         <b> A alegria de viver está na doação.
    </string>

    <!-- Configurações de CPU -->

    <string name="pref_cpu_freq">Frequencia</string>
    <string name="pref_cpu_freqmax">Max. Frequencia</string>
    <string name="pref_cpu_freqmin">Min. Frequencia</string>
    <string name="pref_cpu_governor">Configurações do Governor</string>
    <string name="perf_live_oc_uc">Live OC/UC</string>
    <string name="perf_live_oc_uc_sum">Controle as Frequencias e Voltage em tempo real!</string>

    <string name="pref_gov_choose">Configurações do Governor</string>
    <string name="pref_gov_choose_sum">Isto irá definir o seu governador favorito!</string>

    <string name="pref_gov_set">Configurações do Governor especifico</string>
    <string name="pref_gov_set_sum">Mude as configurações do governador aqui.</string>

    <!-- Memory Fragment -->
    <string name="pref_memory_settings">Configurações de memoria</string>

    <string name="pref_memory_swappiness">Swappiness</string>
    <string name="pref_memory_swappiness_sum">Swappiness define o quão agressivo o kernel irá trocar páginas de memória.</string>

    <string name="pref_dynamic_fsync">Dinamico FSync</string>
    <string name="pref_dynamic_fsync_sum">Dinamico FSync ativa fsync somente quando a tela esta desligada.</string>

    <string name="pref_memory_swap">Swap</string>
    <string name="pref_memory_swap_sum">Criar uma memoria Swap.</string>

    <string name="pref_memory_zcache">zCache</string>
    <string name="pref_memory_zcache_sum">zCache usa CPU-time para um melhor gerenciamento de memoria.</string>

    <string name="pref_memory_zcache_compression">zCache Compressão</string>
    <string name="pref_memory_zcache_compression_sum">Selecione o metodo de compressão para zCache.</string>

    <string name="fstrim_header">Opições Trim</string>
    <string name="fstrim_content">Trim varias partes do seu sistema! Isso pode demorar um pouco.</string>

    <string name="has_journal_dialog_header">Problema detectado</string>

    <string name="has_journal_dialog">Parece que a sua /data não possui <b>has_journal</b> Recurso ativo.
                            Reinicie em recuperação e execute o seguinte comando via adb shell: <br /> <br />
                            <b>tune2fs -O has_journal /dev/block/mmcblk1p25</b>
    </string>

    <!-- IO Scheduler -->
    <string name="io_scheduler">IO Scheduler</string>

    <!-- Configurações de GPU -->
    <string name="pref_gpu_control_enable">GPU Control</string>
    <string name="pref_gpu_control_enable_sum">Isso ativa o controle de driver da GPU. Ele lida com overclocking/undervolting também
                                            com algumas coisas basicas da GPU.</string>
    <string name="pref_gpu_max_freq">Max. Frequencia</string>
    <string name="pref_gpu_max_freq_sum">Isto irá definir a freqüência máxima GPU. Padrão é 200 MHz.</string>

    <!-- Frequências de GPU -->

    <string-array name="gpu_frequency_list">
        <item>100 MHz</item>
        <item>133 MHz</item>
        <item>160 MHz</item>
        <item>200 MHz</item>
        <item>266 MHz</item>
    </string-array>

    <string-array name="gpu_frequency_list_values">
        <item>100000000</item>
        <item>133333333</item>
        <item>160000000</item>
        <item>200000000</item>
        <item>266666666</item>
    </string-array>

    <!-- Atualização -->
    <string name="pref_updater">Atualização e Backup de Kernel</string>
    <string name="pref_backup_kernel">Backup de Kernel</string>
    <string name="pref_backup_kernel_content">Essa opção ira salvar uma copia do seu kernel atual .</string>

    <string name="pref_updater_kernel">Atualização Kernel</string>
    <string name="pref_updater_kernel_content">Isso ira atualizar seu kernel.</string>

    <string name="pref_restore">Restaurar Backup</string>
    <string name="pref_restore_kernel">Restaurar</string>
    <string name="pref_restore_kernel_content">Restaurar de backup de Kernel.</string>

    <string name="last_backup_from">Ultimo backup</string>
    <string name="backup_from">Backup de </string>
    <string name="restore_from_backup">DVocê quer restaurar o backup de </string>
    <string name="proceed_backup">Proceder com o backup? Isso ira fazer backup de seu kernel atual.</string>

    <!-- Showcase Strings -->
    <string name="showcase_aero_fragment">Bem vindo ao Aero Control!</string>
    <string name="showcase_aero_fragment_sum">Passe da esquerda para a direita para mostrar a gaveta de navegação.
                                                A página que você está olhando é a Visão geral do painel principal.
                                                Há um pequeno resumo de algumas configurações de kernel. Eles estão aqui, você
                                                não é necessario atualizar nada!</string>

    <string name="showcase_memory_fragment_trim">Opções Trim</string>
    <string name="showcase_memory_fragment_trim_sum">Para manter o desempenho do dispositivo, você pode executar o Trim em
                                                    varias partes do sistema operacional. Isso pode demorar um pouco,
                                                    especificamente se você possui muitos dados.</string>

</resources>
