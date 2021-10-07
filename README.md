# Log-netlify
Erro ao publicar o projeto DsCatalog

```shell
1:00:12 PM: Build ready to start
1:00:14 PM: build-image version: 3bcb38c35508b42e9121d4badfe6d8c66fd7a3f0
1:00:14 PM: build-image tag: v4.3.2
1:00:14 PM: buildbot version: 0966611527937161c7edcafc1347bc5a61d77108
1:00:14 PM: Building without cache
1:00:14 PM: Starting to prepare the repo for build
1:00:14 PM: No cached dependencies found. Cloning fresh repo
1:00:14 PM: git clone https://github.com/tiagogomes187/dscatalog-bootcamp-devsuperior
1:00:16 PM: Preparing Git Reference refs/heads/main
1:00:16 PM: Parsing package.json dependencies
1:00:17 PM: Different publish path detected, going to use the one specified in the Netlify configuration file: 'frontweb/build' versus 'build' in the Netlify UI
1:00:17 PM: Starting build script
1:00:17 PM: Installing dependencies
1:00:17 PM: Python version set to 2.7
1:00:18 PM: v16.10.0 is already installed.
1:00:18 PM: Now using node v16.10.0 (npm v7.24.0)
1:00:18 PM: Started restoring cached build plugins
1:00:18 PM: Finished restoring cached build plugins
1:00:19 PM: Attempting ruby version 2.7.2, read from environment
1:00:20 PM: Using ruby version 2.7.2
1:00:20 PM: Using PHP version 8.0
1:00:20 PM: Started restoring cached yarn cache
1:00:20 PM: Finished restoring cached yarn cache
1:00:20 PM: Installing yarn at version 1.22.10
1:00:20 PM: Installing Yarn!
1:00:20 PM: > Downloading tarball...
1:00:20 PM: [1/2]: https://yarnpkg.com/downloads/1.22.10/yarn-v1.22.10.tar.gz --> /tmp/yarn.tar.gz.xHGXDEnYPE
1:00:20 PM:   % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
1:00:20 PM:                                  Dload  Upload   Total   Spent    Left  Speed
1:00:21 PM:   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
1:00:21 PM: 100    81  100    81    0     0    663      0 --:--:-- --:--:-- --:--:--   663
1:00:21 PM: 100    95  100    95    0     0    272      0 --:--:-- --:--:-- --:--:--   272
1:00:21 PM: 100   626  100   626    0     0   1196      0 --:--:-- --:--:-- --:--:--  1196
1:00:21 PM: 100 1215k  100 1215k    0     0  1793k      0 --:--:-- --:--:-- --:--:-- 1793k
1:00:21 PM: [2/2]: https://yarnpkg.com/downloads/1.22.10/yarn-v1.22.10.tar.gz.asc --> /tmp/yarn.tar.gz.xHGXDEnYPE.asc
1:00:21 PM:   % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
1:00:21 PM:                                  Dload  Upload   Total   Spent    Left  Speed
1:00:21 PM:   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
1:00:21 PM: 100    85  100    85    0     0   1931      0 --:--:-- --:--:-- --:--:--  1931
1:00:21 PM: 100    99  100    99    0     0   1337      0 --:--:-- --:--:-- --:--:--  1337
1:00:21 PM: 100   630  100   630    0     0   6176      0 --:--:-- --:--:-- --:--:--  6176
1:00:21 PM: 100   832  100   832    0     0   6351      0 --:--:-- --:--:-- --:--:--  6351
1:00:21 PM: 100   832  100   832    0     0   6351      0 --:--:-- --:--:-- --:--:--     0
1:00:21 PM: > Verifying integrity...
1:00:21 PM: gpg: Signature made Fri 02 Oct 2020 11:17:27 AM UTC
1:00:21 PM: gpg:                using RSA key 6D98490C6F1ACDDD448E45954F77679369475BAA
1:00:21 PM: gpg: Good signature from "Yarn Packaging <yarn@dan.cx>" [unknown]
1:00:21 PM: gpg: WARNING: This key is not certified with a trusted signature!
1:00:21 PM: gpg:          There is no indication that the signature belongs to the owner.
1:00:21 PM: Primary key fingerprint: 72EC F46A 56B4 AD39 C907  BBB7 1646 B01B 86E5 0310
1:00:21 PM:      Subkey fingerprint: 6D98 490C 6F1A CDDD 448E  4595 4F77 6793 6947 5BAA
1:00:21 PM: > GPG signature looks good
1:00:21 PM: > Extracting to ~/.yarn...
1:00:21 PM: > Adding to $PATH...
1:00:22 PM: > Successfully installed Yarn 1.22.10! Please open another terminal where the `yarn` command will now be available.
1:00:22 PM: No yarn workspaces detected
1:00:22 PM: Started restoring cached node modules
1:00:22 PM: Finished restoring cached node modules
1:00:22 PM: Installing NPM modules using Yarn version 1.22.10
1:00:23 PM: yarn install v1.22.10
1:00:23 PM: [1/4] Resolving packages...
1:00:24 PM: [2/4] Fetching packages...
1:00:54 PM: info fsevents@2.3.2: The platform "linux" is incompatible with this module.
1:00:54 PM: info "fsevents@2.3.2" is an optional dependency and failed compatibility check. Excluding it from installation.
1:00:54 PM: info fsevents@1.2.13: The platform "linux" is incompatible with this module.
1:00:54 PM: info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
1:00:54 PM: [3/4] Linking dependencies...
1:00:54 PM: warning " > @testing-library/user-event@13.2.1" has unmet peer dependency "@testing-library/dom@>=7.21.4".
1:00:54 PM: warning " > bootstrap@5.0.2" has unmet peer dependency "@popperjs/core@^2.9.2".
1:01:13 PM: [4/4] Building fresh packages...
1:03:53 PM: error /opt/build/repo/frontweb/node_modules/node-sass: Command failed.
1:03:53 PM: Exit code: 1
1:03:53 PM: Command: node scripts/build.js
1:03:53 PM: Arguments:
1:03:53 PM: Directory: /opt/build/repo/frontweb/node_modules/node-sass
1:03:53 PM: Output:
1:03:53 PM: Building: /opt/buildhome/.nvm/versions/node/v16.10.0/bin/node /opt/build/repo/frontweb/node_modules/node-gyp/bin/node-gyp.js rebuild --verbose --libsass_ext= --libsass_cflags= --libsass_ldflags= --libsass_library=
1:03:53 PM: gyp info it worked if it ends with ok
1:03:53 PM: gyp verb cli [
1:03:53 PM: gyp verb cli   '/opt/buildhome/.nvm/versions/node/v16.10.0/bin/node',
1:03:53 PM: gyp verb cli   '/opt/build/repo/frontweb/node_modules/node-gyp/bin/node-gyp.js',
1:03:53 PM: gyp verb cli   'rebuild',
1:03:53 PM: gyp verb cli   '--verbose',
1:03:53 PM: gyp verb cli   '--libsass_ext=',
1:03:53 PM: gyp verb cli   '--libsass_cflags=',
1:03:53 PM: gyp verb cli   '--libsass_ldflags=',
1:03:53 PM: gyp verb cli   '--libsass_library='
1:03:53 PM: gyp verb cli ]
1:03:53 PM: gyp info using node-gyp@3.8.0
1:03:53 PM: gyp info using node@16.10.0 | linux | x64
1:03:53 PM: Creating deploy upload records
1:03:53 PM: gyp verb command rebuild []
1:03:53 PM: gyp verb command clean []
1:03:53 PM: gyp verb clean removing "build" directory
1:03:53 PM: gyp verb command configure []
1:03:53 PM: gyp verb check python checking for Python executable "python2" in the PATH
1:03:53 PM: gyp verb `which` succeeded python2 /opt/buildhome/python2.7/bin/python2
1:03:53 PM: gyp verb check python version `/opt/buildhome/python2.7/bin/python2 -c "import sys; print "2.7.18
gyp verb check python version .%s.%s" % sys.version_info[:3];"` returned: %j
1:03:53 PM: gyp verb get node dir no --target version specified, falling back to host node version: 16.10.0
1:03:53 PM: gyp verb command install [ '16.10.0' ]
1:03:53 PM: gyp verb install input version string "16.10.0"
1:03:53 PM: gyp verb install installing version: 16.10.0
1:03:53 PM: gyp verb install --ensure was passed, so won't reinstall if already installed
gyp verb install version not already installed, continuing with install 16.10.0
1:03:53 PM: gyp verb ensuring nodedir is created /opt/buildhome/.node-gyp/16.10.0
1:03:53 PM: gyp verb created nodedir /opt/buildhome/.node-gyp
1:03:53 PM: gyp http GET https://nodejs.org/download/release/v16.10.0/node-v16.10.0-headers.tar.gz
1:03:53 PM: gyp http 200 https://nodejs.org/download/release/v16.10.0/node-v16.10.0-headers.tar.gz
1:03:53 PM: gyp verb extracted file from tarball include/node/common.gypi
1:03:53 PM: gyp verb extracted file from tarball include/node/config.gypi
1:03:53 PM: Failed during stage 'building site': Build script returned non-zero exit code: 1
1:03:53 PM: gyp verb extracted file from tarball include/node/node.h
1:03:53 PM: gyp verb extracted file from tarball include/node/node_api.h
1:03:53 PM: gyp verb extracted file from tarball include/node/js_native_api.h
1:03:53 PM: gyp verb extracted file from tarball include/node/js_native_api_types.h
1:03:53 PM: gyp verb extracted file from tarball include/node/node_api_types.h
1:03:53 PM: gyp verb extracted file from tarball include/node/node_buffer.h
1:03:53 PM: gyp verb extracted file from tarball include/node/node_object_wrap.h
1:03:53 PM: gyp verb extracted file from tarball include/node/node_version.h
1:03:53 PM: gyp verb extracted file from tarball include/node/v8config.h
1:03:53 PM: gyp verb extracted file from tarball include/node/v8-internal.h
1:03:53 PM: gyp verb extracted file from tarball include/node/v8-platform.h
1:03:53 PM: gyp verb extracted file from tarball include/node/v8-version.h
1:03:53 PM: gyp verb extracted file from tarball include/node/v8-profiler.h
1:03:53 PM: gyp verb extracted file from tarball include/node/v8.h
1:03:53 PM: gyp verb extracted file from tarball include/node/libplatform/libplatform-export.h
1:03:53 PM: gyp verb extracted file from tarball include/node/libplatform/libplatform.h
1:03:53 PM: gyp verb extracted file from tarball include/node/libplatform/v8-tracing.h
1:03:53 PM: gyp verb extracted file from tarball include/node/cppgc/common.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/aix.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/android-ifaddrs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/bsd.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/darwin.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/errno.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/linux.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/os390.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/posix.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/stdint-msvc2008.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/sunos.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/threadpool.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/tree.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/unix.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/win.h
1:03:53 PM: gyp verb extracted file from tarball include/node/uv/version.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/aes.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/asn1.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/asn1_mac.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/asn1t.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/async.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/asyncerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/bio.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/bioerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/blowfish.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/bnerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/buffer.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/buffererr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/camellia.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/cast.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/cmac.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/cms.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/cmserr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/comp.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/comperr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/conf_api.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/conferr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/cryptoerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ct.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/cterr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/des.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/dh.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/dherr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/dsa.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/dsaerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/dtls1.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ebcdic.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ecdh.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ecdsa.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/engine.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/engineerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/err.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/sslerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/hmac.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/idea.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/kdf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/kdferr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/lhash.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/md2.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/md4.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/md5.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/mdc2.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/modes.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/objects.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/objectserr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ocsp.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ocsperr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/x509err.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/opensslv.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/pem.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/pem2.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/pkcs12.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/pkcs12err.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/pkcs7.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/pkcs7err.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/rand.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/rand_drbg.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/randerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/rc2.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/rc4.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/rc5.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ripemd.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/rsa.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/rsaerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/safestack.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/seed.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/sha.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/srp.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/srtp.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ssl2.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/evperr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/stack.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/store.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/storeerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/symhacks.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ts.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/tserr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/txt_db.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ui.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/uierr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/whrlpool.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ec.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/x509v3.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/x509v3err.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/crypto.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/evp.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/e_os2.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/pemerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ssl3.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ossl_typ.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ssl.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/tls1.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/ecerr.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/x509.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/x509_vfy.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/asn1err.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/bn.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/obj_mac.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86_64/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN32/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64-ARM/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64-ARM/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64-ARM/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64-ARM/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64-ARM/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/VC-WIN64A/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix-gcc/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/aix64-gcc/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin-i386-cc/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-x86_64-cc/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-aarch64/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-armv4/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-elf/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-ppc64le/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x32/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux-x86_64/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux32-s390x/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-s390x/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris-x86-gcc/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/solaris64-x86_64-gcc/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb content checksum node-v16.10.0-headers.tar.gz efb4b0133ab578f99cb9abb990817cafafea15bae1c07716565cece513070621
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/BSD-x86/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/darwin64-arm64-cc/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm_avx2/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm_avx2/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm_avx2/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm_avx2/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/asm_avx2/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-mips64/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-riscv64/no-asm/crypto/include/internal/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-riscv64/no-asm/crypto/include/internal/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-riscv64/no-asm/crypto/buildinf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-riscv64/no-asm/include/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/archs/linux64-riscv64/no-asm/include/progs.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/bn_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/dso_conf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/opensslconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/dso_conf_asm.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/bn_conf_asm.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/bn_conf_no-asm.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/dso_conf_no-asm.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/opensslconf_asm.h
1:03:53 PM: gyp verb extracted file from tarball include/node/openssl/opensslconf_no-asm.h
1:03:53 PM: gyp verb extracted file from tarball include/node/zconf.h
1:03:53 PM: gyp verb extracted file from tarball include/node/zlib.h
1:03:53 PM: gyp verb tarball done parsing tarball
1:03:53 PM: gyp verb check download content checksum, need to download `SHASUMS256.txt`...
1:03:53 PM: gyp verb checksum url https://nodejs.org/download/release/v16.10.0/SHASUMS256.txt
1:03:53 PM: gyp http GET https://nodejs.org/download/release/v16.10.0/SHASUMS256.txt
1:03:53 PM: gyp http 200 https://nodejs.org/download/release/v16.10.0/SHASUMS256.txt
1:03:53 PM: gyp verb checksum data {"node-v16.10.0-aix-ppc64.tar.gz":"2142ee042206c5064b19fc034d8d03c7291d0177341a3b55f80d0a3b44ee32de","node-v16.10.0-darwin-arm64.tar.gz":"dfdaf4149365e170929b99692520388e89f618e8d64ddd3ded7126bccf4583ed","node-v16.10.0-darwin-arm64.tar.xz":"c6eaaf06ed1b18150794a68d7a211cf8e9dd794be4def36da6a5ebb136c702c8","node-v16.10.0-darwin-x64.tar.gz":"66a42483908aabd6d5fb19e9f3cebd6927dc84206b75b8801d9e010815083906","node-v16.10.0-darwin-x64.tar.xz":"0635879c2ae0ddff5dcd6dcce9649c0119d005a16f376b8331979a0709fc97e4","node-v16.10.0-headers.tar.gz":"efb4b0133ab578f99cb9abb990817cafafea15bae1c07716565cece513070621","node-v16.10.0-headers.tar.xz":"8f90343307892774cd26d0cbc48743f04667a2f450852b5b01d4da4ac2295195","node-v16.10.0-linux-arm64.tar.gz":"2675ca64c50badd609907b2149f7c021cce52248e08f984a4102d4f390794f57","node-v16.10.0-linux-arm64.tar.xz":"a9b477ea5c376729d59b39ecbb9bc5597b792a00ec11afbdf1e502b9b2557fb2","node-v16.10.0-linux-armv7l.tar.gz":"2d2c63fc7f974419437194f854204a2728095dbe124d1a6f782f3ac6201d8e02","node-v16.10.0-linux-armv7l.tar.xz":"b52d3be99a05a4975ce492f4e010274f66ff6449824accd57a87fd29ab5d054a","node-v16.10.0-linux-ppc64le.tar.gz":"3fa8d29fec4db4097968e1023e9c82aad866a09e96d3201efc213902d5b85059","node-v16.10.0-linux-ppc64le.tar.xz":"dbaef9f49547a0ce396d7fadb4863978f2c38989801af3d2ebaa55270722ea6a","node-v16.10.0-linux-s390x.tar.gz":"a7197fd1e3fad30ea9f40fccddce16cc39a155a48c7f41f0ea04024ec793683d","node-v16.10.0-linux-s390x.tar.xz":"ca6bcb2098622880433b14323d4789ce7034eb94cd0a77134feed975ab5483ed","node-v16.10.0-linux-x64.tar.gz":"bca7f42ea3e61938cc28868614bb37908111b9ff190fe8022fa9954651b5665d","node-v16.10.0-linux-x64.tar.xz":"00c4de617038fe7bd60efd9303b83abe5a5df830a9221687e20408404e307c4e","node-v16.10.0.pkg":"6fa8b76a7c0e3e5c4b0ccb48ddbf0d37fb625ba74dec7c21df40ca80fea164d5","node-v16.10.0.tar.gz":"69b09bb0c4cd9add7eb501b1625a405b15d6ce53596e98b863c8d066e0b6b202","node-v16.10.0.tar.xz":"97dc1aca232b4911e0b9e5a23a03200ab8ef05157e03c732315b579481bf7912","node-v16.10.0-win-x64.7z":"c8ed55a1e9285ec261c95457226cdcbbed12cff3cdb715f464de185d9c5f2f0b","node-v16.10.0-win-x64.zip":"269ef35a91e7e8ce107ed09ca17e70d2feb448cf46ed6dbda86ac95cb90c5344","node-v16.10.0-win-x86.7z":"d1fe8079361f9e524e471173f92de4b47a8c7ecd20fee557283fb524b3e31c9a","node-v16.10.0-win-x86.zip":"4f00121f999d681a20a83f51683a5acd736d983d866bef86689c54865b34b861","node-v16.10.0-x64.msi":"eaa59fd94899078f118130bf31448a4d307cce3f3687cff99fa71e1a89c0b1b6","node-v16.10.0-x86.msi":"d4a800849ab7f0ae701a5c29a3c0f79e491efb0124bdc3e695cc5dc2faef2088","win-x64/node.exe":"3a1b4319a963655d7c72b32ea942f4e17db2d37f625039581eb8b1996c3fff85","win-x64/node.lib":"774524a2b7c2806a8141a430ce9c6bffb9e8f78ce6bc095ec8fa26a333ff7cef","win-x64/node_pdb.7z":"19d5c41f19e5358fb6ba08e45373a5cfb9248b894471c594d4ba0f7309d2de02","win-x64/node_pdb.zip":"14f8057e9daefb6e034a6f6d1e259aa301c99067d95ca15c57b03ffdb5258bac","win-x86/node.exe":"2f13f5ef2a4ce07eee5d938b2ad4e6bd629decfcb45d8d8d594b9f2a8f30805d","win-x86/node.lib":"1827162a03517e9a4897bd0195e601216d4ffb3680b11db4599166d0e76b6e98","win-x86/node_pdb.7z":"fb6b5b947acdacba035933befca57ec5e7c24bf7907579416f0244261a023f60","win-x86/node_pdb.zip":"3f2f144955744ae2030fd870ed45df5f0adbd63f26489a21cd37257de52f272c"}
1:03:53 PM: gyp verb download contents checksum {"node-v16.10.0-headers.tar.gz":"efb4b0133ab578f99cb9abb990817cafafea15bae1c07716565cece513070621"}
1:03:53 PM: gyp verb validating download checksum for node-v16.10.0-headers.tar.gz (efb4b0133ab578f99cb9abb990817cafafea15bae1c07716565cece513070621 == efb4b0133ab578f99cb9abb990817cafafea15bae1c07716565cece513070621)
1:03:53 PM: gyp verb get node dir target node version installed: 16.10.0
1:03:53 PM: gyp verb build dir attempting to create "build" dir: /opt/build/repo/frontweb/node_modules/node-sass/build
1:03:53 PM: gyp verb build dir "build" dir needed to be created? /opt/build/repo/frontweb/node_modules/node-sass/build
1:03:53 PM: gyp verb build/config.gypi creating config file
1:03:53 PM: gyp verb build/config.gypi writing out config file: /opt/build/repo/frontweb/node_modules/node-sass/build/config.gypi
1:03:53 PM: (node:1342) [DEP0150] DeprecationWarning: Setting process.config is deprecated. In the future the property will be read-only.
1:03:53 PM: (Use `node --trace-deprecation ...` to show where the warning was created)
1:03:53 PM: gyp verb config.gypi checking for gypi file: /opt/build/repo/frontweb/node_modules/node-sass/config.gypi
1:03:53 PM: gyp verb common.gypi checking for gypi file: /opt/build/repo/frontweb/node_modules/node-sass/common.gypi
1:03:53 PM: gyp verb gyp gyp format was not specified; forcing "make"
1:03:53 PM: gyp info spawn /opt/buildhome/python2.7/bin/python2
1:03:53 PM: gyp info spawn args [
1:03:53 PM: gyp info spawn args   '/opt/build/repo/frontweb/node_modules/node-gyp/gyp/gyp_main.py',
1:03:53 PM: gyp info spawn args   'binding.gyp',
1:03:53 PM: gyp info spawn args   '-f',
1:03:53 PM: gyp info spawn args   'make',
1:03:53 PM: gyp info spawn args   '-I',
1:03:53 PM: gyp info spawn args   '/opt/build/repo/frontweb/node_modules/node-sass/build/config.gypi',
1:03:53 PM: gyp info spawn args   '-I',
1:03:53 PM: gyp info spawn args   '/opt/build/repo/frontweb/node_modules/node-gyp/addon.gypi',
1:03:53 PM: gyp info spawn args   '-I',
1:03:53 PM: gyp info spawn args   '/opt/buildhome/.node-gyp/16.10.0/include/node/common.gypi',
1:03:53 PM: gyp info spawn args   '-Dlibrary=shared_library',
1:03:53 PM: gyp info spawn args   '-Dvisibility=default',
1:03:53 PM: gyp info spawn args   '-Dnode_root_dir=/opt/buildhome/.node-gyp/16.10.0',
1:03:53 PM: gyp info spawn args   '-Dnode_gyp_dir=/opt/build/repo/frontweb/node_modules/node-gyp',
1:03:53 PM: gyp info spawn args   '-Dnode_lib_file=/opt/buildhome/.node-gyp/16.10.0/<(target_arch)/node.lib',
1:03:53 PM: gyp info spawn args   '-Dmodule_root_dir=/opt/build/repo/frontweb/node_modules/node-sass',
1:03:53 PM: gyp info spawn args   '-Dnode_engine=v8',
1:03:53 PM: gyp info spawn args   '--depth=.',
1:03:53 PM: gyp info spawn args   '--no-parallel',
1:03:53 PM: gyp info spawn args   '--generator-output',
1:03:53 PM: gyp info spawn args   'build',
1:03:53 PM: gyp info spawn args   '-Goutput_dir=.'
1:03:53 PM: gyp info spawn args ]
1:03:53 PM: gyp verb command build []
1:03:53 PM: gyp verb build type Release
1:03:53 PM: gyp verb architecture x64
1:03:53 PM: gyp verb node dev dir /opt/buildhome/.node-gyp/16.10.0
1:03:53 PM: gyp verb `which` succeeded for `make` /usr/bin/make
1:03:53 PM: gyp info spawn make
1:03:53 PM: gyp info spawn args [ 'V=1', 'BUILDTYPE=Release', '-C', 'build' ]
1:03:53 PM: make: Entering directory '/opt/build/repo/frontweb/node_modules/node-sass/build'
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/ast.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/ast.o ../src/libsass/src/ast.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/ast_fwd_decl.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/ast_fwd_decl.o ../src/libsass/src/ast_fwd_decl.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/backtrace.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/backtrace.o ../src/libsass/src/backtrace.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/base64vlq.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/base64vlq.o ../src/libsass/src/base64vlq.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/bind.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/bind.o ../src/libsass/src/bind.cpp
1:03:53 PM:   cc '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer  -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/cencode.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/cencode.o ../src/libsass/src/cencode.c
1:03:53 PM: ../src/libsass/src/cencode.c: In function ‘base64_encode_block’:
1:03:53 PM: ../src/libsass/src/cencode.c:48:11: warning: this statement may fall through [-Wimplicit-fallthrough=]
1:03:53 PM:    48 |    result = (fragment & 0x003) << 4;
1:03:53 PM:       |    ~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
1:03:53 PM: ../src/libsass/src/cencode.c:52:2: note: here
1:03:53 PM:    52 |  case step_B:
1:03:53 PM:       |  ^~~~
1:03:53 PM: ../src/libsass/src/cencode.c:62:11: warning: this statement may fall through [-Wimplicit-fallthrough=]
1:03:53 PM:    62 |    result = (fragment & 0x00f) << 2;
1:03:53 PM:       |    ~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
1:03:53 PM: ../src/libsass/src/cencode.c:66:2: note: here
1:03:53 PM:    66 |  case step_C:
1:03:53 PM:       |  ^~~~
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/check_nesting.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/check_nesting.o ../src/libsass/src/check_nesting.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/color_maps.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/color_maps.o ../src/libsass/src/color_maps.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/info Visit https://yarnpkg.com/en/docs/cli/install for documentation about this command.
1:03:53 PM: opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/constants.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/constants.o ../src/libsass/src/constants.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/context.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/context.o ../src/libsass/src/context.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/cssize.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/cssize.o ../src/libsass/src/cssize.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/emitter.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/emitter.o ../src/libsass/src/emitter.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/environment.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/environment.o ../src/libsass/src/environment.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/error_handling.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/error_handling.o ../src/libsass/src/error_handling.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/eval.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/eval.o ../src/libsass/src/eval.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/expand.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/expand.o ../src/libsass/src/expand.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/extend.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/extend.o ../src/libsass/src/extend.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/file.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/file.o ../src/libsass/src/file.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/functions.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/functions.o ../src/libsass/src/functions.cpp
1:03:53 PM: ../src/libsass/src/functions.cpp: In function ‘void Sass::Functions::handle_utf8_error(const Sass::ParserState&, Sass::Backtraces)’:
1:03:53 PM: ../src/libsass/src/functions.cpp:110:20: warning: catching polymorphic type ‘class utf8::invalid_code_point’ by value [-Wcatch-value=]
1:03:53 PM:   110 |       catch (utf8::invalid_code_point) {
1:03:53 PM:       |                    ^~~~~~~~~~~~~~~~~~
1:03:53 PM: ../src/libsass/src/functions.cpp:114:20: warning: catching polymorphic type ‘class utf8::not_enough_room’ by value [-Wcatch-value=]
1:03:53 PM:   114 |       catch (utf8::not_enough_room) {
1:03:53 PM:       |                    ^~~~~~~~~~~~~~~
1:03:53 PM: ../src/libsass/src/functions.cpp:118:20: warning: catching polymorphic type ‘class utf8::invalid_utf8’ by value [-Wcatch-value=]
1:03:53 PM:   118 |       catch (utf8::invalid_utf8) {
1:03:53 PM:       |                    ^~~~~~~~~~~~
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/inspect.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/inspect.o ../src/libsass/src/inspect.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/json.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/json.o ../src/libsass/src/json.cpp
1:03:53 PM: ../src/libsass/src/json.cpp: In function ‘char* json_encode_string(const char*)’:
1:03:53 PM: ../src/libsass/src/json.cpp:405:15: warning: catching polymorphic type ‘class std::exception’ by value [-Wcatch-value=]
1:03:53 PM:   405 |   catch (std::exception) {
1:03:53 PM:       |               ^~~~~~~~~
1:03:53 PM: ../src/libsass/src/json.cpp: In function ‘char* json_stringify(const JsonNode*, const char*)’:
1:03:53 PM: ../src/libsass/src/json.cpp:424:15: warning: catching polymorphic type ‘class std::exception’ by value [-Wcatch-value=]
1:03:53 PM:   424 |   catch (std::exception) {
1:03:53 PM:       |               ^~~~~~~~~
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/lexer.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/lexer.o ../src/libsass/src/lexer.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/listize.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/listize.o ../src/libsass/src/listize.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/memory/SharedPtr.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/memory/SharedPtr.o ../src/libsass/src/memory/SharedPtr.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/node.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/node.o ../src/libsass/src/node.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/operators.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/operators.o ../src/libsass/src/operators.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/output.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/output.o ../src/libsass/src/output.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/parser.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/parser.o ../src/libsass/src/parser.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/plugins.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/plugins.o ../src/libsass/src/plugins.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/position.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/position.o ../src/libsass/src/position.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/prelexer.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/prelexer.o ../src/libsass/src/prelexer.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/remove_placeholders.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/remove_placeholders.o ../src/libsass/src/remove_placeholders.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/sass.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/sass.o ../src/libsass/src/sass.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/sass2scss.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/sass2scss.o ../src/libsass/src/sass2scss.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/sass_context.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/sass_context.o ../src/libsass/src/sass_context.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/sass_functions.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/sass_functions.o ../src/libsass/src/sass_functions.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/sass_util.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/sass_util.o ../src/libsass/src/sass_util.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/sass_values.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/sass_values.o ../src/libsass/src/sass_values.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/source_map.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/source_map.o ../src/libsass/src/source_map.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/subset_map.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/subset_map.o ../src/libsass/src/subset_map.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/to_c.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/to_c.o ../src/libsass/src/to_c.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/to_value.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/to_value.o ../src/libsass/src/to_value.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/units.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/units.o ../src/libsass/src/units.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/utf8_string.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/utf8_string.o ../src/libsass/src/utf8_string.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/util.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/util.o ../src/libsass/src/util.cpp
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=libsass' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DLIBSASS_VERSION="3.5.5"' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -std=gnu++14 -std=c++0x -fexceptions -frtti -MMD -MF ./Release/.deps/Release/obj.target/libsass/src/libsass/src/values.o.d.raw   -c -o Release/obj.target/libsass/src/libsass/src/values.o ../src/libsass/src/values.cpp
1:03:53 PM:   rm -f Release/obj.target/src/sass.a && ar crs Release/obj.target/src/sass.a Release/obj.target/libsass/src/libsass/src/ast.o Release/obj.target/libsass/src/libsass/src/ast_fwd_decl.o Release/obj.target/libsass/src/libsass/src/backtrace.o Release/obj.target/libsass/src/libsass/src/base64vlq.o Release/obj.target/libsass/src/libsass/src/bind.o Release/obj.target/libsass/src/libsass/src/cencode.o Release/obj.target/libsass/src/libsass/src/check_nesting.o Release/obj.target/libsass/src/libsass/src/color_maps.o Release/obj.target/libsass/src/libsass/src/constants.o Release/obj.target/libsass/src/libsass/src/context.o Release/obj.target/libsass/src/libsass/src/cssize.o Release/obj.target/libsass/src/libsass/src/emitter.o Release/obj.target/libsass/src/libsass/src/environment.o Release/obj.target/libsass/src/libsass/src/error_handling.o Release/obj.target/libsass/src/libsass/src/eval.o Release/obj.target/libsass/src/libsass/src/expand.o Release/obj.target/libsass/src/libsass/src/extend.o Release/obj.target/libsass/src/libsass/src/file.o Release/obj.target/libsass/src/libsass/src/functions.o Release/obj.target/libsass/src/libsass/src/inspect.o Release/obj.target/libsass/src/libsass/src/json.o Release/obj.target/libsass/src/libsass/src/lexer.o Release/obj.target/libsass/src/libsass/src/listize.o Release/obj.target/libsass/src/libsass/src/memory/SharedPtr.o Release/obj.target/libsass/src/libsass/src/node.o Release/obj.target/libsass/src/libsass/src/operators.o Release/obj.target/libsass/src/libsass/src/output.o Release/obj.target/libsass/src/libsass/src/parser.o Release/obj.target/libsass/src/libsass/src/plugins.o Release/obj.target/libsass/src/libsass/src/position.o Release/obj.target/libsass/src/libsass/src/prelexer.o Release/obj.target/libsass/src/libsass/src/remove_placeholders.o Release/obj.target/libsass/src/libsass/src/sass.o Release/obj.target/libsass/src/libsass/src/sass2scss.o Release/obj.target/libsass/src/libsass/src/sass_context.o Release/obj.target/libsass/src/libsass/src/sass_functions.o Release/obj.target/libsass/src/libsass/src/sass_util.o Release/obj.target/libsass/src/libsass/src/sass_values.o Release/obj.target/libsass/src/libsass/src/source_map.o Release/obj.target/libsass/src/libsass/src/subset_map.o Release/obj.target/libsass/src/libsass/src/to_c.o Release/obj.target/libsass/src/libsass/src/to_value.o Release/obj.target/libsass/src/libsass/src/units.o Release/obj.target/libsass/src/libsass/src/utf8_string.o Release/obj.target/libsass/src/libsass/src/util.o Release/obj.target/libsass/src/libsass/src/values.o
1:03:53 PM:   rm -rf "Release/sass.a" && cp -af "Release/obj.target/src/sass.a" "Release/sass.a"
1:03:53 PM:   g++ '-DNODE_GYP_MODULE_NAME=binding' '-DUSING_UV_SHARED=1' '-DUSING_V8_SHARED=1' '-DV8_DEPRECATION_WARNINGS=1' '-DV8_DEPRECATION_WARNINGS' '-DV8_IMMINENT_DEPRECATION_WARNINGS' '-D_GLIBCXX_USE_CXX11_ABI=1' '-D_LARGEFILE_SOURCE' '-D_FILE_OFFSET_BITS=64' '-D__STDC_FORMAT_MACROS' '-DOPENSSL_NO_PINSHARED' '-DOPENSSL_THREADS' '-DBUILDING_NODE_EXTENSION' -I/opt/buildhome/.node-gyp/16.10.0/include/node -I/opt/buildhome/.node-gyp/16.10.0/src -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/config -I/opt/buildhome/.node-gyp/16.10.0/deps/openssl/openssl/include -I/opt/buildhome/.node-gyp/16.10.0/deps/uv/include -I/opt/buildhome/.node-gyp/16.10.0/deps/zlib -I/opt/buildhome/.node-gyp/16.10.0/deps/v8/include -I../../nan -I../src/libsass/include  -fPIC -pthread -Wall -Wextra -Wno-unused-parameter -m64 -O3 -fno-omit-frame-pointer -fno-rtti -fno-exceptions -std=gnu++14 -std=c++0x -MMD -MF ./Release/.deps/Release/obj.target/binding/src/binding.o.d.raw   -c -o Release/obj.target/binding/src/binding.o ../src/binding.cpp
1:03:53 PM: In file included from /opt/buildhome/.node-gyp/16.10.0/include/node/v8.h:30,
1:03:53 PM:                  from /opt/buildhome/.node-gyp/16.10.0/include/node/node.h:63,
1:03:53 PM:                  from ../../nan/nan.h:56,
1:03:53 PM:                  from ../src/binding.cpp:1:
1:03:53 PM: /opt/buildhome/.node-gyp/16.10.0/include/node/v8-internal.h: In function ‘void v8::internal::PerformCastCheck(T*)’:
1:03:53 PM: /opt/buildhome/.node-gyp/16.10.0/include/node/v8-internal.h:489:38: error: ‘remove_cv_t’ is not a member of ‘std’; did you mean ‘remove_cv’?
1:03:53 PM:   489 |             !std::is_same<Data, std::remove_cv_t<T>>::value>::Perform(data);
1:03:53 PM:       |                                      ^~~~~~~~~~~
1:03:53 PM:       |                                      remove_cv
1:03:53 PM: /opt/buildhome/.node-gyp/16.10.0/include/node/v8-internal.h:489:38: error: ‘remove_cv_t’ is not a member of ‘std’; did you mean ‘remove_cv’?
1:03:53 PM:   489 |             !std::is_same<Data, std::remove_cv_t<T>>::value>::Perform(data);
1:03:53 PM:       |                                      ^~~~~~~~~~~
1:03:53 PM:       |                                      remove_cv
1:03:53 PM: /opt/buildhome/.node-gyp/16.10.0/include/node/v8-internal.h:489:50: error: template argument 2 is invalid
1:03:53 PM:   489 |             !std::is_same<Data, std::remove_cv_t<T>>::value>::Perform(data);
1:03:53 PM:       |                                                  ^
1:03:53 PM: /opt/buildhome/.node-gyp/16.10.0/include/node/v8-internal.h:489:63: error: ‘::Perform’ has not been declared
1:03:53 PM:   489 |             !std::is_same<Data, std::remove_cv_t<T>>::value>::Perform(data);
1:03:53 PM:       |                                                               ^~~~~~~
1:03:53 PM: ../src/binding.cpp: In function ‘Nan::NAN_METHOD_RETURN_TYPE render(Nan::NAN_METHOD_ARGS_TYPE)’:
1:03:53 PM: ../src/binding.cpp:284:98: warning: cast between incompatible function types from ‘void (*)(uv_work_t*)’ {aka ‘void (*)(uv_work_s*)’} to ‘uv_after_work_cb’ {aka ‘void (*)(uv_work_s*, int)’} [-Wcast-function-type]
1:03:53 PM:   284 |     int status = uv_queue_work(uv_default_loop(), &ctx_w->request, compile_it, (uv_after_work_cb)MakeCallback);
1:03:53 PM:       |                                                                                                  ^~~~~~~~~~~~
1:03:53 PM: ../src/binding.cpp: In function ‘Nan::NAN_METHOD_RETURN_TYPE render_file(Nan::NAN_METHOD_ARGS_TYPE)’:
1:03:53 PM: ../src/binding.cpp:320:98: warning: cast between incompatible function types from ‘void (*)(uv_work_t*)’ {aka ‘void (*)(uv_work_s*)’} to ‘uv_after_work_cb’ {aka ‘void (*)(uv_work_s*, int)’} [-Wcast-function-type]
1:03:53 PM:   320 |     int status = uv_queue_work(uv_default_loop(), &ctx_w->request, compile_it, (uv_after_work_cb)MakeCallback);
1:03:53 PM:       |                                                                                                  ^~~~~~~~~~~~
1:03:53 PM: In file included from ../../nan/nan.h:56,
1:03:53 PM:                  from ../src/binding.cpp:1:
1:03:53 PM: ../src/binding.cpp: At global scope:
1:03:53 PM: /opt/buildhome/.node-gyp/16.10.0/include/node/node.h:821:43: warning: cast between incompatible function types from ‘void (*)(Nan::ADDON_REGISTER_FUNCTION_ARGS_TYPE)’ {aka ‘void (*)(v8::Local<v8::Object>)’} to ‘node::addon_register_func’ {aka ‘void (*)(v8::Local<v8::Object>, v8::Local<v8::Value>, void*)’} [-Wcast-function-type]
1:03:53 PM:   821 |       (node::addon_register_func) (regfunc),                          \
1:03:53 PM:       |                                           ^
1:03:53 PM: /opt/buildhome/.node-gyp/16.10.0/include/node/node.h:855:3: note: in expansion of macro ‘NODE_MODULE_X’
1:03:53 PM:   855 |   NODE_MODULE_X(modname, regfunc, NULL, 0)  // NOLINT (readability/null_usage)
1:03:53 PM:       |   ^~~~~~~~~~~~~
1:03:53 PM: ../src/binding.cpp:358:1: note: in expansion of macro ‘NODE_MODULE’
1:03:53 PM:   358 | NODE_MODULE(binding, RegisterModule);
1:03:53 PM:       | ^~~~~~~~~~~
1:03:53 PM: make: *** [binding.target.mk:133: Release/obj.target/binding/src/binding.o] Error 1
1:03:53 PM: make: Leaving directory '/opt/build/repo/frontweb/node_modules/node-sass/build'
1:03:53 PM: gyp ERR! build error
1:03:53 PM: gyp ERR! stack Error: `make` failed with exit code: 2
1:03:53 PM: gyp ERR! stack     at ChildProcess.onExit (/opt/build/repo/frontweb/node_modules/node-gyp/lib/build.js:262:23)
1:03:53 PM: gyp ERR! stack     at ChildProcess.emit (node:events:390:28)
1:03:53 PM: gyp ERR! stack     at Process.ChildProcess._handle.onexit (node:internal/child_process:290:12)
1:03:53 PM: gyp ERR! System Linux 4.19.167+
1:03:53 PM: gyp ERR! command "/opt/buildhome/.nvm/versions/node/v16.10.0/bin/node" "/opt/build/repo/frontweb/node_modules/node-gyp/bin/node-gyp.js" "rebuild" "--verbose" "--libsass_ext=" "--libsass_cflags=" "--libsass_ldflags=" "--libsass_library="
1:03:53 PM: gyp ERR! cwd /opt/build/repo/frontweb/node_modules/node-sass
1:03:53 PM: gyp ERR! node -v v16.10.0
1:03:53 PM: gyp ERR! node-gyp -v v3.8.0
1:03:53 PM: gyp ERR! not ok
1:03:53 PM: Build failed with error code: 1
1:03:53 PM: Error during Yarn install
1:03:53 PM: Build was terminated: Build script returned non-zero exit code: 1
1:03:53 PM: Failing build: Failed to build site
````
