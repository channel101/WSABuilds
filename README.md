<div align="center">
  <picture>
    <img align="center" height="20%" width="20%" src="https://github.com/MustardChef/WSABuilds/assets/68516357/35cd1d5d-e464-4eb8-a676-b451341f65ad" alt="WSABuilds logo" />
  </picture>

  <h2>MagiskOnWSA (For Windows™ 10 and 11)</h2>
  <h5>Windows Subsystem For Android™ (WSA) with Google Play Services, Magisk, and KernelSU</h5>

  <a href="https://discord.gg/2thee7zzHZ">
    <img align="center" src="https://invidget.switchblade.xyz/2thee7zzHZ" style="width: 400px;" alt="Discord server" />
  </a>
</div>

<br/>

<p align="center">
  <a href="https://github.com/MustardChef/WSABuilds#downloads">
    <img src="https://img.shields.io/github/downloads/MustardChef/WSABuilds/total?label=Total%20Downloads&amp;style=for-the-badge" alt="Total downloads" />
  </a>
  <a href="https://forum.xda-developers.com/t/wsabuilds-latest-windows-subsystem-for-android-wsa-builds-for-windows-10-and-11-with-magisk-and-google-play-store.4545087/">
    <img src="https://img.shields.io/badge/XDA%20Developers-WSABuilds-EA7100?style=for-the-badge&amp;logoColor=white&amp;logo=XDA-Developers" alt="XDA thread" />
  </a>
  <a href="https://ko-fi.com/N4N0K08AC">
    <img alt="ko-fi" src="https://ko-fi.com/img/githubbutton_sm.svg" />
  </a>
</p>

---

> [!IMPORTANT]
> <details>
> <summary><strong>Apps crashing, not starting, or stuck on loading/splash screen after <code>1st September 2026</code>? Update to the latest LTS release.</strong></summary>
>
> ### Update to the latest LTS release
>
> - **Windows 11 x64**  
>   https://github.com/MustardChef/WSABuilds/releases/tag/Windows_11_2407.40000.4.0_LTS_8
> - **Windows 10 x64**  
>   https://github.com/MustardChef/WSABuilds/releases/tag/Windows_10_2407.40000.4.0_LTS_8
>
> If apps that worked before still fail after updating:
> 1. Clear app data/cache.
> 2. Reinstall the app.
> 3. If needed, perform a clean install (backup first).
>
> Please report results via GitHub Issues and/or the WSA Community Discord.
> </details>

> [!CAUTION]
> <details>
> <summary><strong>Known WSA/GApps stability issues on Windows 11 since June 2025</strong></summary>
>
> GApps builds have had crashes on Windows 11 builds after June 2025.
>
> Ongoing fixes and upgrades are tracked here:  
> https://github.com/MustardChef/WSABuilds/issues/700
>
> ### Current workarounds
>
> - **Recommended fix for builds containing GApps (Google Play Store/Services):**  
>   https://github.com/MustardChef/WSABuilds/issues/593#issuecomment-3172749449
> - Use builds without GApps (`NoGApps` in archive name).
> - Older WSA builds (2211/2210) are known to work.
>
> Updates/discussion:  
> https://github.com/MustardChef/WSABuilds/issues/593
> </details>

> [!TIP]
> To view current bugfixes, planned improvements, and project progress, refer to:  
> https://github.com/users/MustardChef/projects/5

---

## Downloads

<table>
  <thead>
    <tr>
      <th rowspan="2">Operating System</th>
      <th rowspan="2">Channel</th>
      <th colspan="2">Download Page</th>
    </tr>
    <tr>
      <th>x64 / x86</th>
      <th>ARM64</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2" align="center">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/e/e6/Windows_11_logo.svg"
          width="200"
          alt="Windows 11"
          loading="lazy"
        />
      </td>
      <td><strong>Pre-release</strong></td>
      <td>
        <a href="https://github.com/MustardChef/WSABuilds/releases/tag/Windows_11_2407.40000.4.0_LTS_8">
          <img
            alt="Download Windows 11 Pre-release (x64)"
            src="https://img.shields.io/badge/Download-Windows%2011%20Pre--Release%20x64-orange?style=for-the-badge&logo=windows11"
          />
        </a>
      </td>
      <td>
        <a href="https://github.com/MustardChef/WSABuilds/releases/tag/Windows_11_2407.40000.4.0_LTS_8_arm64">
          <img
            alt="Download Windows 11 Pre-release (arm64)"
            src="https://img.shields.io/badge/Download-Windows%2011%20Pre--Release%20arm64-orange?style=for-the-badge&logo=windows11"
          />
        </a>
      </td>
    </tr>
    <tr>
      <td><strong>Stable</strong></td>
      <td>
        <a href="https://github.com/MustardChef/WSABuilds/releases/tag/Windows_11_2407.40000.4.0_LTS_8">
          <img
            alt="Download Windows 11 Stable (x64)"
            src="https://img.shields.io/badge/Download-Windows%2011%20Stable%20x64-blue?style=for-the-badge&logo=windows11"
          />
        </a>
      </td>
      <td>
        <a href="https://github.com/MustardChef/WSABuilds/releases/tag/Windows_11_2407.40000.4.0_LTS_8_arm64">
          <img
            alt="Download Windows 11 Stable (arm64)"
            src="https://img.shields.io/badge/Download-Windows%2011%20Stable%20arm64-blue?style=for-the-badge&logo=windows11"
          />
        </a>
      </td>
    </tr>
    <tr>
      <td rowspan="2" align="center">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/0/05/Windows_10_Logo.svg"
          width="200"
          alt="Windows 10"
          loading="lazy"
        />
      </td>
      <td><strong>Pre-release</strong></td>
      <td>
        <a href="https://github.com/MustardChef/WSABuilds/releases/tag/Windows_10_2407.40000.4.0_LTS_8">
          <img
            alt="Download Windows 10 Pre-release (x64)"
            src="https://img.shields.io/badge/Download-Windows%2010%20Pre--Release%20x64-orange?style=for-the-badge&logo=windows"
          />
        </a>
      </td>
      <td rowspan="2" align="center">—</td>
    </tr>
    <tr>
      <td><strong>Stable</strong></td>
      <td>
        <a href="https://github.com/MustardChef/WSABuilds/releases/tag/Windows_10_2407.40000.4.0_LTS_8">
          <img
            alt="Download Windows 10 Stable (x64)"
            src="https://img.shields.io/badge/Download-Windows%2010%20Stable%20x64-blue?style=for-the-badge&logo=windows"
          />
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://img.icons8.com/color/240/null/windows-11.png" width="50" alt="Windows 11 icon" loading="lazy" />
        <strong>&amp;</strong>
        <img src="https://img.icons8.com/color/240/null/windows-10.png" width="50" alt="Windows 10 icon" loading="lazy" />
      </td>
      <td><strong>Older Builds</strong></td>
      <td colspan="2">
        <a href="./Documentation/WSABuilds/OldBuilds.md">
          <img
            alt="Windows 10/11 Older Builds"
            src="https://img.shields.io/badge/Windows%2010%2F11-Older%20Builds-red?style=for-the-badge"
          />
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://img.icons8.com/color/240/null/windows-11.png" width="50" alt="Windows 11 icon" loading="lazy" />
        <strong>&amp;</strong>
        <img src="https://img.icons8.com/color/240/null/windows-10.png" width="50" alt="Windows 10 icon" loading="lazy" />
      </td>
      <td><strong>Custom Builds</strong></td>
      <td colspan="2">
        <a href="https://github.com/MustardChef/WSAMagiskDelta">
          <img
            alt="Windows 10/11 Magisk Delta"
            src="https://img.shields.io/badge/Windows%2010%2F11-Magisk%20Delta-382bef?style=for-the-badge"
          />
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/f/f5/App_Installer_icon.svg"
          width="80"
          alt="MSIX source icon"
          loading="lazy"
        />
      </td>
      <td><strong>.msix Sources</strong></td>
      <td colspan="2">
        <a href="https://github.com/MustardChef/WSAPackages">
          <img
            alt="Download .msix Sources"
            src="https://img.shields.io/badge/Download-.msix%20Sources-3A6B35?style=for-the-badge&logo=github&logoColor=white"
          />
        </a>
      </td>
    </tr>
  </tbody>
</table>

---

## Requirements

<table>
  <thead>
    <tr>
      <th></th>
      <th><img src="https://upload.wikimedia.org/wikipedia/commons/e/e6/Windows_11_logo.svg" style="width: 200px;" alt="Windows 11"/></th>
      <th><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Windows_10_Logo.svg" style="width: 200px;" alt="Windows 10"/></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2">
        <img height="60" width="60" src="https://img.icons8.com/fluency/96/null/windows-update--v1.png" style="float:left;" alt="Windows build"/>
        <strong>Windows Build Number</strong>
      </td>
      <td>Windows™ 11: Build 22000.526 or higher.</td>
      <td>
        Windows™ 10: 22H2 10.0.19045.2311 or higher.<br/><br/>
        <b><i>May work on Windows™ 10: 20H1 10.0.19041.264 or higher.</i></b><sup>1</sup><br/><br/>
        <sub><sup>1. You may need KB5014032, then KB5022834 for these older builds:
          <a href="https://www.catalog.update.microsoft.com/Search.aspx?q=KB5014032">KB5014032</a>,
          <a href="https://www.catalog.update.microsoft.com/Search.aspx?q=KB5022834">KB5022834</a>
        </sup></sub>
      </td>
    </tr>
    <tr>
      <td colspan="2"><i><b>Custom/modified Windows installations (e.g., ReviOS, Tiny10/11, Ghost Spectre) may have issues running WSA.</b></i></td>
    </tr>
    <tr>
      <td>
        <img height="60" width="60" src="https://img.icons8.com/external-smashingstocks-flat-smashing-stocks/66/null/external-RAM-technology-and-devices-smashingstocks-flat-smashing-stocks.png" style="float:left;" alt="RAM"/>
        <strong>RAM</strong>
      </td>
      <td colspan="2">
        <ul>
          <li>4–6 GB (Not recommended)</li>
          <li>8 GB (Minimum)</li>
          <li>16 GB (Recommended)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <img height="60" width="60" src="https://img.icons8.com/3d-fluency/94/null/electronics.png" style="float:left;" alt="Processor"/>
        <strong>Processor</strong>
      </td>
      <td colspan="2"><b><i>CPU Architecture: x86_64 or arm64</i></b></td>
    </tr>
    <tr>
      <td>Your PC should meet basic Windows™ 11 hardware guidance (e.g., Core i3 8th Gen / Ryzen 3000 / Snapdragon 8c or newer).</td>
      <td>
        N/A<br/><br/>
        Recommended: check Windows 11 supported CPU lists:<br/>
        <a href="https://learn.microsoft.com/en-gb/windows-hardware/design/minimum/windows-processor-requirements">Supported CPU list</a>
      </td>
    </tr>
    <tr>
      <td>
        <img height="60" width="60" src="https://img.icons8.com/3d-fluency/94/null/video-card.png" style="float:left;" alt="GPU"/>
        <strong>GPU</strong>
      </td>
      <td colspan="2">
        Any compatible Intel, AMD, or Nvidia GPU.<br/>
        GPU performance may vary depending on compatibility with WSA.
        <br/><br/>
        <details>
          <summary><strong>Users with Intel HD Graphics 530 and older</strong></summary>
          WSA may not start or may show graphical glitches. This is a known issue and older iGPUs are not officially supported.<br/>
          Use this guide to switch GPU/Microsoft Basic Renderer:<br/>
          <a href="https://github.com/MustardChef/WSABuilds/blob/master/Documentation/Usage%20Guides/General%20Usage%20Guides/ChangingGPU.md">ChangingGPU.md</a>
        </details>
        <br/>
        <details>
          <summary><strong>Users with Nvidia GPUs</strong></summary>
          Nvidia GPUs may cause startup or graphical issues in some systems.<br/>
          Use this guide to switch GPU/Microsoft Basic Renderer:<br/>
          <a href="https://github.com/MustardChef/WSABuilds/blob/master/Documentation/Usage%20Guides/General%20Usage%20Guides/ChangingGPU.md">ChangingGPU.md</a>
        </details>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <img height="60" width="60" src="https://img.icons8.com/3d-fluency/94/null/ssd.png" style="float:left;" alt="Storage"/>
        <strong>Storage</strong>
      </td>
      <td colspan="2">
        <b><i>Solid-state drive (Recommended)</i></b><br/>
        OR<br/>
        <b><i>Hard Disk Drive (HDD)</i></b> (Not recommended)
      </td>
    </tr>
    <tr>
      <td colspan="2"><b><i>Minimum free space: at least 10GB on system drive (C:\)</i></b></td>
    </tr>
    <tr>
      <td>
        <img height="60" width="60" src="https://img.icons8.com/stickers/100/null/storage.png" style="float:left;" alt="Partition"/>
        <strong>Partition</strong>
      </td>
      <td colspan="2"><b><i>NTFS only.</i></b> WSA cannot be installed on exFAT partitions.</td>
    </tr>
    <tr>
      <td rowspan="3">
        <img height="58" width="66" src="https://user-images.githubusercontent.com/68516357/230764789-ad8f7361-4a3b-49a8-a8e9-24fdc87d5781.png" style="float:left;" alt="Windows features"/>
        <strong>Windows Features Needed</strong>
      </td>
      <td colspan="2">Virtual Machine Platform enabled</td>
    </tr>
    <tr>
      <td colspan="2">Windows Hypervisor Platform enabled</td>
    </tr>
    <tr>
      <td colspan="2">
        <sub><b><i>Enable via <code>OptionalFeatures.exe</code> (Win + R), then apply changes.</i></b></sub>
      </td>
    </tr>
    <tr>
      <td>
        <img height="60" width="60" src="https://user-images.githubusercontent.com/68516357/230759907-5d11950e-1b17-4811-8f4e-a0f82e598079.png" style="float:left;" alt="Virtualization"/>
        <strong>Virtualization</strong>
      </td>
      <td colspan="2">
        Virtualization must be supported and enabled in BIOS/UEFI and Optional Features.<br/>
        <a href="https://support.microsoft.com/en-us/windows/enable-virtualization-on-windows-11-pcs-c5578302-6e43-4b4b-a449-8ced115f58e1">Guide to enable virtualization</a>
      </td>
    </tr>
  </tbody>
</table>

---

> [!TIP]
> <details>
> <summary><strong>WSA End Of Support (EoS) Information</strong></summary>
>
> Microsoft ended WSA support, and Amazon Appstore support ended beginning **March 5, 2025**.
>
> Sources:  
> - https://github.com/microsoft/WSA/discussions/536  
> - https://learn.microsoft.com/en-us/windows/android/wsa/
>
> ---
>
> WSABuilds entered LTS for WSA versions ≥ 2311.40000.5.0.  
> Magisk, KernelSU, and GApps versions continue to be updated in new releases.
>
> The repository will remain available and support continues for users.
> </details>

<details>
  <summary><strong>Next LTS and Non-LTS Release Dates</strong></summary>

### WSABuilds LTS 8 Hotfix (v2407.40000.4.0)
~~`Friday 4th September 2026`~~ **Available now** (Stable and Pre-release in Downloads)

### WSABuilds LTS 7 Hotfix (v2407.40000.4.0)
~~`Sunday 4th January 2026`~~ **Available now** (Stable and Pre-release in Downloads)

### Non-LTS Build Update (v2407.40000.4.0_v2)
~~`Monday 2nd June 2025`~~ **Available now** (Stable release buttons in Downloads)

### WSABuilds LTS 7 (v2407.40000.4.0)
~~`Monday 2nd June 2025`~~ **Available now** (Pre-release buttons in Downloads)

### Non-LTS Build Update (v2407.40000.4.0)
~~`Monday 9th December 2024`~~ **Available now** (Stable release buttons in Downloads)

### WSABuilds LTS 6 (v2407.40000.4.0)
~~`Monday 9th December 2024`~~ **Available now** (Pre-release buttons in Downloads)

### Non-LTS Build Update (v2407.40000.0.0)
~~`Thursday 5th December 2024`~~ **Available now** (Stable release buttons in Downloads)

### WSABuilds LTS 5 (v2407.40000.0.0)
~~`Thursday 5th December 2024`~~ **Available now** (Pre-release buttons in Downloads)

### WSABuilds LTS 4 (v2407.40000.0.0)
~~`Monday 15th July 2024`~~ **Available now** (Pre-release buttons in Downloads)

### WSABuilds LTS 3 (v2311.40000.5.0)
~~`Monday 03rd June 2024`~~ **Available now** (Pre-release buttons in Downloads)

### WSABuilds LTS 2 (v2311.40000.5.0)
~~`Friday 03rd May 2024`~~ **Available now** (Pre-release buttons in Downloads)

### WSABuilds LTS 1 (v2311.40000.5.0)
~~`Wednesday 03rd April 2024`~~ **Available now** (Pre-release buttons in Downloads)

</details>

---

## Documentation

- <img height="24" src="https://img.icons8.com/color/96/null/software-installer.png" alt="Installation icon"/> [Installation](https://github.com/MustardChef/WSABuilds/blob/master/Documentation/WSABuilds/Installation.md)
- <img height="24" src="https://img.icons8.com/external-flaticons-flat-flat-icons/64/null/external-updating-tools-and-material-ecommerce-flaticons-flat-flat-icons.png" alt="Updating icon"/> [Updating](https://github.com/MustardChef/WSABuilds/blob/master/Documentation/WSABuilds/Updating.md)
- <img height="24" src="https://img.icons8.com/color/96/null/uninstall-programs.png" alt="Uninstallation icon"/> [Uninstallation](https://github.com/MustardChef/WSABuilds/blob/master/Documentation/WSABuilds/Uninstallation.md)
- <img height="24" src="https://img.icons8.com/fluency/96/cloud-backup-restore.png" alt="Backup icon"/> [Backup and Restore Userdata](https://github.com/MustardChef/WSABuilds/blob/master/Documentation/WSABuilds/Backup%20and%20Restore.md)
- <img height="24" src="https://img.icons8.com/3d-fluency/94/null/help.png" alt="FAQ icon"/> [FAQ](https://github.com/MustardChef/WSABuilds/blob/master/Documentation/WSABuilds/FAQ.md)
- <img height="24" src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/64/external-compatibility-relationship-flaticons-lineal-color-flat-icons-2.png" alt="Compatibility icon"/> [App Compatibility](https://github.com/MustardChef/WSABuilds/blob/master/Documentation/WSABuilds/App%20Compatibility.md)
- <img height="24" src="https://img.icons8.com/external-xnimrodx-lineal-color-xnimrodx/96/null/external-guide-education-xnimrodx-lineal-color-xnimrodx.png" alt="Usage guides icon"/> [Usage Guides](https://github.com/MustardChef/WSABuilds/blob/master/Documentation/WSABuilds/Usage%20Guide.md)
- <img height="24" src="https://img.icons8.com/external-soft-fill-juicy-fish/96/null/external-bug-coding-and-development-soft-fill-soft-fill-juicy-fish-2.png" alt="Issues icon"/> [Having Issues?](https://github.com/MustardChef/WSABuilds/blob/master/Documentation/WSABuilds/Having%20Issues.md)
- <img height="24" src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/64/null/external-credits-movie-theater-flaticons-lineal-color-flat-icons.png" alt="Credits icon"/> [Credits](https://github.com/MustardChef/WSABuilds/blob/master/Documentation/WSABuilds/Credits.md)
