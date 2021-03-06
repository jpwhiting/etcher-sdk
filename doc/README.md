[etcher-sdk](README.md)

# etcher-sdk

## Index

### Classes

* [Adapter](classes/adapter.md)
* [AlignedReadableState](classes/alignedreadablestate.md)
* [BZip2Source](classes/bzip2source.md)
* [BalenaS3Source](classes/balenas3source.md)
* [BlockDevice](classes/blockdevice.md)
* [BlockDeviceAdapter](classes/blockdeviceadapter.md)
* [BlockReadStream](classes/blockreadstream.md)
* [BlockTransformStream](classes/blocktransformstream.md)
* [BlockWriteStream](classes/blockwritestream.md)
* [BlocksVerificationError](classes/blocksverificationerror.md)
* [CRC32Hasher](classes/crc32hasher.md)
* [ChecksumVerificationError](classes/checksumverificationerror.md)
* [CompressedSource](classes/compressedsource.md)
* [ConfiguredSource](classes/configuredsource.md)
* [CountingHashStream](classes/countinghashstream.md)
* [CountingWritable](classes/countingwritable.md)
* [DmgSource](classes/dmgsource.md)
* [DriverlessDevice](classes/driverlessdevice.md)
* [DriverlessDeviceAdapter$](classes/driverlessdeviceadapter_.md)
* [File](classes/file.md)
* [GZipSource](classes/gzipsource.md)
* [Http](classes/http.md)
* [MultiDestination](classes/multidestination.md)
* [MultiDestinationError](classes/multidestinationerror.md)
* [MultiDestinationVerifier](classes/multidestinationverifier.md)
* [NotCapable](classes/notcapable.md)
* [RandomAccessZipSource](classes/randomaccesszipsource.md)
* [Scanner](classes/scanner.md)
* [SingleUseStreamSource](classes/singleusestreamsource.md)
* [SourceDestination](classes/sourcedestination.md)
* [SourceDestinationFs](classes/sourcedestinationfs.md)
* [SourceDisk](classes/sourcedisk.md)
* [SourceRandomAccessReader](classes/sourcerandomaccessreader.md)
* [SourceSource](classes/sourcesource.md)
* [SparseFilterStream](classes/sparsefilterstream.md)
* [SparseReadStream](classes/sparsereadstream.md)
* [SparseStreamVerifier](classes/sparsestreamverifier.md)
* [SparseTransformStream](classes/sparsetransformstream.md)
* [SparseWriteStream](classes/sparsewritestream.md)
* [StreamLimiter](classes/streamlimiter.md)
* [StreamVerifier](classes/streamverifier.md)
* [StreamZipSource](classes/streamzipsource.md)
* [UsbbootDeviceAdapter](classes/usbbootdeviceadapter.md)
* [UsbbootDrive](classes/usbbootdrive.md)
* [VerificationError](classes/verificationerror.md)
* [Verifier](classes/verifier.md)
* [XzSource](classes/xzsource.md)
* [ZipSource](classes/zipsource.md)

### Interfaces

* [AdapterSourceDestination](interfaces/adaptersourcedestination.md)
* [AlignedLockableBuffer](interfaces/alignedlockablebuffer.md)
* [Block](interfaces/block.md)
* [BlocksWithChecksum](interfaces/blockswithchecksum.md)
* [CreateReadStreamOptions](interfaces/createreadstreamoptions.md)
* [CreateSparseReadStreamOptions](interfaces/createsparsereadstreamoptions.md)
* [DrivelistDrive](interfaces/drivelistdrive.md)
* [ExecResult](interfaces/execresult.md)
* [Metadata](interfaces/metadata.md)
* [MultiDestinationProgress](interfaces/multidestinationprogress.md)
* [MultiDestinationState](interfaces/multidestinationstate.md)
* [Operation](interfaces/operation.md)
* [PipeSourceToDestinationsResult](interfaces/pipesourcetodestinationsresult.md)
* [ProgressEvent](interfaces/progressevent.md)
* [SourceTransform](interfaces/sourcetransform.md)
* [SparseReadable](interfaces/sparsereadable.md)
* [SparseReaderState](interfaces/sparsereaderstate.md)
* [SparseStreamChunk](interfaces/sparsestreamchunk.md)
* [SparseWritable](interfaces/sparsewritable.md)
* [TmpFileResult](interfaces/tmpfileresult.md)
* [WifiConfig](interfaces/wificonfig.md)

### Type aliases

* [AnyHasher](README.md#anyhasher)
* [ChecksumType](README.md#checksumtype)
* [ConfigureFunction](README.md#configurefunction)
* [Constructor](README.md#constructor)
* [Name](README.md#name)
* [OnFailFunction](README.md#onfailfunction)
* [OnProgressFunction](README.md#onprogressfunction)
* [OperationCommand](README.md#operationcommand)
* [WriteStep](README.md#writestep)
* [XXHash](README.md#xxhash)

### Variables

* [BITS](README.md#const-bits)
* [CHUNK_SIZE](README.md#const-chunk_size)
* [DEFAULT_ALIGNMENT](README.md#const-default_alignment)
* [DISKPART_DELAY](README.md#const-diskpart_delay)
* [DISKPART_RETRIES](README.md#const-diskpart_retries)
* [DriverlessDeviceAdapter](README.md#const-driverlessdeviceadapter)
* [ISIZE_LENGTH](README.md#const-isize_length)
* [MBR_LAST_PRIMARY_PARTITION](README.md#const-mbr_last_primary_partition)
* [NETWORK_SETTINGS_KEYS](README.md#const-network_settings_keys)
* [NO_MATCHING_FILE_MSG](README.md#const-no_matching_file_msg)
* [PARTITION_FIELDS](README.md#const-partition_fields)
* [PATTERN](README.md#const-pattern)
* [PROGRESS_EMISSION_INTERVAL](README.md#const-progress_emission_interval)
* [ProgressBlockReadStream](README.md#const-progressblockreadstream)
* [ProgressBlockWriteStream](README.md#const-progressblockwritestream)
* [ProgressHashStream](README.md#const-progresshashstream)
* [ProgressReadStream](README.md#const-progressreadstream)
* [ProgressSparseTransformStream](README.md#const-progresssparsetransformstream)
* [ProgressSparseWriteStream](README.md#const-progresssparsewritestream)
* [ProgressWritable](README.md#const-progresswritable)
* [ProgressWriteStream](README.md#const-progresswritestream)
* [READ_TRIES](README.md#const-read_tries)
* [RETRY_BASE_TIMEOUT](README.md#const-retry_base_timeout)
* [RWMutex](README.md#rwmutex)
* [SCAN_INTERVAL](README.md#const-scan_interval)
* [TMP_DIR](README.md#const-tmp_dir)
* [TMP_RANDOM_BYTES](README.md#const-tmp_random_bytes)
* [TRIES](README.md#const-tries)
* [UNMOUNT_ON_SUCCESS_TIMEOUT_MS](README.md#const-unmount_on_success_timeout_ms)
* [USBBOOT_RPI_COMPUTE_MODULE_NAMES](README.md#const-usbboot_rpi_compute_module_names)
* [WIN32_FIRST_BYTES_TO_KEEP](README.md#const-win32_first_bytes_to_keep)
* [XXHASH_SEED](README.md#const-xxhash_seed)
* [debug](README.md#const-debug)
* [getCrc](README.md#const-getcrc)
* [getRaspberrypiUsbboot](README.md#const-getraspberrypiusbboot)
* [getUnmountDisk](README.md#const-getunmountdisk)
* [getXXHash](README.md#const-getxxhash)
* [parseFileIndexAsync](README.md#const-parsefileindexasync)
* [speedometer](README.md#speedometer)
* [unbzip2Stream](README.md#unbzip2stream)
* [zlib](README.md#zlib)

### Functions

* [alignedLockableBufferSlice](README.md#alignedlockablebufferslice)
* [asCallback](README.md#ascallback)
* [attachMutex](README.md#attachmutex)
* [blockmapToBlocks](README.md#blockmaptoblocks)
* [blocksLength](README.md#blockslength)
* [blocksVerificationErrorMessage](README.md#blocksverificationerrormessage)
* [clean](README.md#const-clean)
* [configure](README.md#const-configure)
* [copy](README.md#const-copy)
* [createBuffer](README.md#createbuffer)
* [createHasher](README.md#createhasher)
* [createNetworkConfigFiles](README.md#const-createnetworkconfigfiles)
* [createSparseReaderStateIterator](README.md#createsparsereaderstateiterator)
* [difference](README.md#difference)
* [driveKey](README.md#const-drivekey)
* [execFileAsync](README.md#const-execfileasync)
* [execute](README.md#const-execute)
* [executeOperation](README.md#const-executeoperation)
* [getDiskDeviceType](README.md#const-getdiskdevicetype)
* [getEta](README.md#geteta)
* [getFileStreamFromZipStream](README.md#const-getfilestreamfromzipstream)
* [getPartitionIndex](README.md#const-getpartitionindex)
* [getRootStream](README.md#getrootstream)
* [isAlignedLockableBuffer](README.md#isalignedlockablebuffer)
* [isSourceTransform](README.md#issourcetransform)
* [isTransientError](README.md#istransienterror)
* [isntNull](README.md#isntnull)
* [looksLikeComputeModule](README.md#lookslikecomputemodule)
* [makeClassEmitProgressEvents](README.md#makeclassemitprogressevents)
* [matchSupportedExtensions](README.md#matchsupportedextensions)
* [nmWifiConfig](README.md#const-nmwificonfig)
* [pad](README.md#const-pad)
* [pipeRegularSourceToDestination](README.md#piperegularsourcetodestination)
* [pipeSourceToDestinations](README.md#pipesourcetodestinations)
* [pipeSparseSourceToDestination](README.md#pipesparsesourcetodestination)
* [randomFilePath](README.md#const-randomfilepath)
* [runDiskpart](README.md#const-rundiskpart)
* [runVerifier](README.md#runverifier)
* [sparseStreamToBuffer](README.md#sparsestreamtobuffer)
* [streamToBuffer](README.md#streamtobuffer)
* [tmpFile](README.md#const-tmpfile)
* [tmpFileDisposer](README.md#const-tmpfiledisposer)
* [verifyOrGenerateChecksum](README.md#verifyorgeneratechecksum)

### Object literals

* [ACTIONS](README.md#const-actions)

## Type aliases

###  AnyHasher

Ƭ **AnyHasher**: *[CRC32Hasher](classes/crc32hasher.md) | Hash | XXHash | XXHash64*

*Defined in [lib/sparse-stream/shared.ts:75](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/sparse-stream/shared.ts#L75)*

___

###  ChecksumType

Ƭ **ChecksumType**: *"crc32" | "sha1" | "sha256" | "xxhash32" | "xxhash64"*

*Defined in [lib/sparse-stream/shared.ts:26](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/sparse-stream/shared.ts#L26)*

___

###  ConfigureFunction

Ƭ **ConfigureFunction**: *function*

*Defined in [lib/source-destination/configured-source/configured-source.ts:45](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configured-source.ts#L45)*

#### Type declaration:

▸ (`disk`: Disk, `config`: any): *Promise‹void›*

**Parameters:**

Name | Type |
------ | ------ |
`disk` | Disk |
`config` | any |

___

###  Constructor

Ƭ **Constructor**: *object*

*Defined in [lib/source-destination/progress.ts:25](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/progress.ts#L25)*

#### Type declaration:

___

###  Name

Ƭ **Name**: *"balena" | "resin"*

*Defined in [lib/source-destination/balena-s3-source.ts:28](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/balena-s3-source.ts#L28)*

___

###  OnFailFunction

Ƭ **OnFailFunction**: *function*

*Defined in [lib/multi-write.ts:60](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/multi-write.ts#L60)*

#### Type declaration:

▸ (`destination`: [SourceDestination](classes/sourcedestination.md), `error`: [Error](classes/notcapable.md#static-error)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`destination` | [SourceDestination](classes/sourcedestination.md) |
`error` | [Error](classes/notcapable.md#static-error) |

___

###  OnProgressFunction

Ƭ **OnProgressFunction**: *function*

*Defined in [lib/multi-write.ts:65](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/multi-write.ts#L65)*

#### Type declaration:

▸ (`progress`: [MultiDestinationProgress](interfaces/multidestinationprogress.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`progress` | [MultiDestinationProgress](interfaces/multidestinationprogress.md) |

___

###  OperationCommand

Ƭ **OperationCommand**: *"configure" | "copy"*

*Defined in [lib/source-destination/configured-source/configure.ts:28](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L28)*

___

###  WriteStep

Ƭ **WriteStep**: *"flashing" | "verifying" | "finished"*

*Defined in [lib/multi-write.ts:34](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/multi-write.ts#L34)*

___

###  XXHash

Ƭ **XXHash**: *typeof xxhash*

*Defined in [lib/lazy.ts:21](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/lazy.ts#L21)*

## Variables

### `Const` BITS

• **BITS**: *64 | 32* = arch === 'x64' || arch === 'aarch64' ? 64 : 32

*Defined in [lib/source-destination/source-destination.ts:50](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/source-destination.ts#L50)*

___

### `Const` CHUNK_SIZE

• **CHUNK_SIZE**: *number* = 1024 ** 2

*Defined in [lib/constants.ts:19](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/constants.ts#L19)*

___

### `Const` DEFAULT_ALIGNMENT

• **DEFAULT_ALIGNMENT**: *512* = 512

*Defined in [lib/constants.ts:23](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/constants.ts#L23)*

___

### `Const` DISKPART_DELAY

• **DISKPART_DELAY**: *2000* = 2000

*Defined in [lib/diskpart.ts:27](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/diskpart.ts#L27)*

___

### `Const` DISKPART_RETRIES

• **DISKPART_RETRIES**: *5* = 5

*Defined in [lib/diskpart.ts:28](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/diskpart.ts#L28)*

___

### `Const` DriverlessDeviceAdapter

• **DriverlessDeviceAdapter**: *undefined | [DriverlessDeviceAdapter$](classes/driverlessdeviceadapter_.md)* = platform === 'win32' ? DriverlessDeviceAdapter$ : undefined

*Defined in [lib/scanner/adapters/driverless.ts:105](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/scanner/adapters/driverless.ts#L105)*

___

### `Const` ISIZE_LENGTH

• **ISIZE_LENGTH**: *4* = 4

*Defined in [lib/source-destination/gzip.ts:23](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/gzip.ts#L23)*

___

### `Const` MBR_LAST_PRIMARY_PARTITION

• **MBR_LAST_PRIMARY_PARTITION**: *4* = 4

*Defined in [lib/source-destination/configured-source/configure.ts:36](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L36)*

___

### `Const` NETWORK_SETTINGS_KEYS

• **NETWORK_SETTINGS_KEYS**: *string[]* = [
	'wifiSsid',
	'wifiKey',
	'ip',
	'netmask',
	'gateway',
	'routeMetric',
]

*Defined in [lib/source-destination/configured-source/operations/configure.ts:23](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/operations/configure.ts#L23)*

___

### `Const` NO_MATCHING_FILE_MSG

• **NO_MATCHING_FILE_MSG**: *"Can't find a matching file in this zip archive"* = "Can't find a matching file in this zip archive"

*Defined in [lib/constants.ts:20](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/constants.ts#L20)*

___

### `Const` PARTITION_FIELDS

• **PARTITION_FIELDS**: *string[]* = ['partition', 'to.partition', 'from.partition']

*Defined in [lib/source-destination/configured-source/configure.ts:35](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L35)*

___

### `Const` PATTERN

• **PATTERN**: *RegExp‹›* = /PHYSICALDRIVE(\d+)/i

*Defined in [lib/diskpart.ts:29](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/diskpart.ts#L29)*

___

### `Const` PROGRESS_EMISSION_INTERVAL

• **PROGRESS_EMISSION_INTERVAL**: *number* = 1000 / 2

*Defined in [lib/constants.ts:17](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/constants.ts#L17)*

___

### `Const` ProgressBlockReadStream

• **ProgressBlockReadStream**: *(Anonymous class) & [BlockReadStream](classes/blockreadstream.md)* = makeClassEmitProgressEvents(
	BlockReadStream,
	'bytesRead',
	'bytesRead',
	PROGRESS_EMISSION_INTERVAL,
)

*Defined in [lib/block-read-stream.ts:122](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/block-read-stream.ts#L122)*

___

### `Const` ProgressBlockWriteStream

• **ProgressBlockWriteStream**: *(Anonymous class) & [BlockWriteStream](classes/blockwritestream.md)* = makeClassEmitProgressEvents(
	BlockWriteStream,
	'bytesWritten',
	'bytesWritten',
	PROGRESS_EMISSION_INTERVAL,
)

*Defined in [lib/block-write-stream.ts:124](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/block-write-stream.ts#L124)*

___

### `Const` ProgressHashStream

• **ProgressHashStream**: *(Anonymous class) & [CountingHashStream](classes/countinghashstream.md)* = makeClassEmitProgressEvents(
	CountingHashStream,
	'bytesWritten',
	'bytesWritten',
	PROGRESS_EMISSION_INTERVAL,
)

*Defined in [lib/source-destination/source-destination.ts:81](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/source-destination.ts#L81)*

___

### `Const` ProgressReadStream

• **ProgressReadStream**: *(Anonymous class) & ReadStream* = makeClassEmitProgressEvents(
	ReadStream,
	'bytesRead',
	'bytesRead',
	PROGRESS_EMISSION_INTERVAL,
)

*Defined in [lib/source-destination/file.ts:35](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/file.ts#L35)*

___

### `Const` ProgressSparseTransformStream

• **ProgressSparseTransformStream**: *(Anonymous class) & [SparseTransformStream](classes/sparsetransformstream.md)* = makeClassEmitProgressEvents(
	SparseTransformStream,
	'bytesWritten',
	'position',
	PROGRESS_EMISSION_INTERVAL,
)

*Defined in [lib/sparse-stream/sparse-transform-stream.ts:85](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/sparse-stream/sparse-transform-stream.ts#L85)*

___

### `Const` ProgressSparseWriteStream

• **ProgressSparseWriteStream**: *(Anonymous class) & [SparseWriteStream](classes/sparsewritestream.md)* = makeClassEmitProgressEvents(
	SparseWriteStream,
	'bytesWritten',
	'position',
	PROGRESS_EMISSION_INTERVAL,
)

*Defined in [lib/sparse-stream/sparse-write-stream.ts:148](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/sparse-stream/sparse-write-stream.ts#L148)*

___

### `Const` ProgressWritable

• **ProgressWritable**: *(Anonymous class) & [CountingWritable](classes/countingwritable.md)* = makeClassEmitProgressEvents(
	CountingWritable,
	'bytesWritten',
	'position',
	PROGRESS_EMISSION_INTERVAL,
)

*Defined in [lib/source-destination/progress.ts:110](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/progress.ts#L110)*

___

### `Const` ProgressWriteStream

• **ProgressWriteStream**: *(Anonymous class) & WriteStream* = makeClassEmitProgressEvents(
	WriteStream,
	'bytesWritten',
	'bytesWritten',
	PROGRESS_EMISSION_INTERVAL,
)

*Defined in [lib/source-destination/file.ts:42](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/file.ts#L42)*

___

### `Const` READ_TRIES

• **READ_TRIES**: *5* = 5

*Defined in [lib/source-destination/file.ts:49](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/file.ts#L49)*

___

### `Const` RETRY_BASE_TIMEOUT

• **RETRY_BASE_TIMEOUT**: *100* = 100

*Defined in [lib/constants.ts:18](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/constants.ts#L18)*

___

###  RWMutex

• **RWMutex**: *[RWMutex](README.md#rwmutex)*

*Defined in [lib/aligned-lockable-buffer.ts:2](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/aligned-lockable-buffer.ts#L2)*

___

### `Const` SCAN_INTERVAL

• **SCAN_INTERVAL**: *1000* = 1000

*Defined in [lib/scanner/adapters/block-device.ts:27](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/scanner/adapters/block-device.ts#L27)*

*Defined in [lib/scanner/adapters/driverless.ts:26](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/scanner/adapters/driverless.ts#L26)*

___

### `Const` TMP_DIR

• **TMP_DIR**: *string* = tmpdir()

*Defined in [lib/tmp.ts:24](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/tmp.ts#L24)*

___

### `Const` TMP_RANDOM_BYTES

• **TMP_RANDOM_BYTES**: *6* = 6

*Defined in [lib/tmp.ts:23](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/tmp.ts#L23)*

___

### `Const` TRIES

• **TRIES**: *5* = 5

*Defined in [lib/tmp.ts:25](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/tmp.ts#L25)*

___

### `Const` UNMOUNT_ON_SUCCESS_TIMEOUT_MS

• **UNMOUNT_ON_SUCCESS_TIMEOUT_MS**: *2000* = 2000

*Defined in [lib/source-destination/block-device.ts:42](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/block-device.ts#L42)*

**`summary`** Time, in milliseconds, to wait before unmounting on success

___

### `Const` USBBOOT_RPI_COMPUTE_MODULE_NAMES

• **USBBOOT_RPI_COMPUTE_MODULE_NAMES**: *string[]* = [
	'0001',
	'RPi-MSD- 0001',
	'File-Stor Gadget',
	'Linux File-Stor_Gadget',
	'Linux File-Stor Gadget',
	'Linux File-Stor Gadget USB Device',
	'Linux File-Stor Gadget Media',
]

*Defined in [lib/scanner/adapters/block-device.ts:28](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/scanner/adapters/block-device.ts#L28)*

___

### `Const` WIN32_FIRST_BYTES_TO_KEEP

• **WIN32_FIRST_BYTES_TO_KEEP**: *number* = 64 * 1024

*Defined in [lib/source-destination/block-device.ts:43](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/block-device.ts#L43)*

___

### `Const` XXHASH_SEED

• **XXHASH_SEED**: *1163150152* = 1163150152

*Defined in [lib/constants.ts:22](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/constants.ts#L22)*

___

### `Const` debug

• **debug**: *IDebugger* = _debug('etcher-sdk:configured-source')

*Defined in [lib/diskpart.ts:25](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/diskpart.ts#L25)*

*Defined in [lib/block-write-stream.ts:29](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/block-write-stream.ts#L29)*

*Defined in [lib/scanner/adapters/block-device.ts:25](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/scanner/adapters/block-device.ts#L25)*

*Defined in [lib/scanner/scanner.ts:22](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/scanner/scanner.ts#L22)*

*Defined in [lib/source-destination/configured-source/configured-source.ts:43](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configured-source.ts#L43)*

___

### `Const` getCrc

• **getCrc**: *(Anonymous function)* = once(() => require('crc') as typeof import('crc'))

*Defined in [lib/lazy.ts:39](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/lazy.ts#L39)*

___

### `Const` getRaspberrypiUsbboot

• **getRaspberrypiUsbboot**: *(Anonymous function)* = once(() => {
	try {
		return require('node-raspberrypi-usbboot') as typeof import('node-raspberrypi-usbboot');
	} catch (e) {
		console.warn('Failed to import node-raspberrypi-usbboot:', e);
	}
})

*Defined in [lib/lazy.ts:23](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/lazy.ts#L23)*

___

### `Const` getUnmountDisk

• **getUnmountDisk**: *(Anonymous function)* = once(() =>
	promisify((require('mountutils') as typeof import('mountutils')).unmountDisk),
)

*Defined in [lib/lazy.ts:35](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/lazy.ts#L35)*

___

### `Const` getXXHash

• **getXXHash**: *(Anonymous function)* = once(
	() => require('xxhash') as typeof import('xxhash'),
)

*Defined in [lib/lazy.ts:31](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/lazy.ts#L31)*

___

### `Const` parseFileIndexAsync

• **parseFileIndexAsync**: *function* = promisify(parseFileIndex)

*Defined in [lib/source-destination/xz.ts:24](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/xz.ts#L24)*

#### Type declaration:

▸ (`arg1`: T1): *Promise‹TResult›*

**Parameters:**

Name | Type |
------ | ------ |
`arg1` | T1 |

___

###  speedometer

• **speedometer**: *[speedometer](README.md#speedometer)*

*Defined in [lib/source-destination/progress.ts:21](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/progress.ts#L21)*

___

###  unbzip2Stream

• **unbzip2Stream**: *[unbzip2Stream](README.md#unbzip2stream)*

*Defined in [lib/source-destination/bzip2.ts:18](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/bzip2.ts#L18)*

___

###  zlib

• **zlib**: *"zlib"*

*Defined in [lib/stream-limiter.ts:18](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/stream-limiter.ts#L18)*

## Functions

###  alignedLockableBufferSlice

▸ **alignedLockableBufferSlice**(`this`: [AlignedLockableBuffer](interfaces/alignedlockablebuffer.md), `start?`: undefined | number, `end?`: undefined | number): *[AlignedLockableBuffer](interfaces/alignedlockablebuffer.md)‹›*

*Defined in [lib/aligned-lockable-buffer.ts:11](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/aligned-lockable-buffer.ts#L11)*

**Parameters:**

Name | Type |
------ | ------ |
`this` | [AlignedLockableBuffer](interfaces/alignedlockablebuffer.md) |
`start?` | undefined &#124; number |
`end?` | undefined &#124; number |

**Returns:** *[AlignedLockableBuffer](interfaces/alignedlockablebuffer.md)‹›*

___

###  asCallback

▸ **asCallback**<**T**>(`promise`: Promise‹T›, `callback`: function): *Promise‹void›*

*Defined in [lib/utils.ts:98](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/utils.ts#L98)*

**Type parameters:**

▪ **T**

**Parameters:**

▪ **promise**: *Promise‹T›*

▪ **callback**: *function*

▸ (`error?`: [Error](classes/notcapable.md#static-error) | null, `value?`: T): *void*

**Parameters:**

Name | Type |
------ | ------ |
`error?` | [Error](classes/notcapable.md#static-error) &#124; null |
`value?` | T |

**Returns:** *Promise‹void›*

___

###  attachMutex

▸ **attachMutex**(`buf`: [Buffer](interfaces/alignedlockablebuffer.md#buffer), `alignment`: number, `lock`: function, `rlock`: function): *[AlignedLockableBuffer](interfaces/alignedlockablebuffer.md)*

*Defined in [lib/aligned-lockable-buffer.ts:20](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/aligned-lockable-buffer.ts#L20)*

**Parameters:**

▪ **buf**: *[Buffer](interfaces/alignedlockablebuffer.md#buffer)*

▪ **alignment**: *number*

▪ **lock**: *function*

▸ (): *Promise‹function›*

▪ **rlock**: *function*

▸ (): *Promise‹function›*

**Returns:** *[AlignedLockableBuffer](interfaces/alignedlockablebuffer.md)*

___

###  blockmapToBlocks

▸ **blockmapToBlocks**(`blockmap`: BlockMap): *[BlocksWithChecksum](interfaces/blockswithchecksum.md)[]*

*Defined in [lib/source-destination/zip.ts:51](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/zip.ts#L51)*

**Parameters:**

Name | Type |
------ | ------ |
`blockmap` | BlockMap |

**Returns:** *[BlocksWithChecksum](interfaces/blockswithchecksum.md)[]*

___

###  blocksLength

▸ **blocksLength**(`blocks`: [BlocksWithChecksum](interfaces/blockswithchecksum.md)[]): *number*

*Defined in [lib/sparse-stream/shared.ts:139](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/sparse-stream/shared.ts#L139)*

**Parameters:**

Name | Type |
------ | ------ |
`blocks` | [BlocksWithChecksum](interfaces/blockswithchecksum.md)[] |

**Returns:** *number*

___

###  blocksVerificationErrorMessage

▸ **blocksVerificationErrorMessage**(`blocksWithChecksum`: [BlocksWithChecksum](interfaces/blockswithchecksum.md), `checksum`: string): *string*

*Defined in [lib/errors.ts:37](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/errors.ts#L37)*

**Parameters:**

Name | Type |
------ | ------ |
`blocksWithChecksum` | [BlocksWithChecksum](interfaces/blockswithchecksum.md) |
`checksum` | string |

**Returns:** *string*

___

### `Const` clean

▸ **clean**(`device`: string): *Promise‹void›*

*Defined in [lib/diskpart.ts:86](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/diskpart.ts#L86)*

**`summary`** Clean a device's partition tables

**`example`** 
diskpart.clean('\\\\.\\PhysicalDrive2')
  .then(...)
  .catch(...)

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`device` | string | device path |

**Returns:** *Promise‹void›*

___

### `Const` configure

▸ **configure**(`disk`: Disk, `options`: object): *Promise‹void›*

*Defined in [lib/source-destination/configured-source/configure.ts:87](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L87)*

**Parameters:**

▪ **disk**: *Disk*

▪`Default value`  **options**: *object*= {}

Name | Type |
------ | ------ |
`config?` | any |

**Returns:** *Promise‹void›*

___

### `Const` copy

▸ **copy**(`sourceFs`: AsyncFsLike, `sourcePath`: string, `destinationFs`: AsyncFsLike, `destinationPath`: string): *Promise‹void›*

*Defined in [lib/source-destination/configured-source/operations/copy.ts:22](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/operations/copy.ts#L22)*

**Parameters:**

Name | Type |
------ | ------ |
`sourceFs` | AsyncFsLike |
`sourcePath` | string |
`destinationFs` | AsyncFsLike |
`destinationPath` | string |

**Returns:** *Promise‹void›*

___

###  createBuffer

▸ **createBuffer**(`size`: number, `alignment`: number): *[AlignedLockableBuffer](interfaces/alignedlockablebuffer.md)*

*Defined in [lib/aligned-lockable-buffer.ts:34](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/aligned-lockable-buffer.ts#L34)*

**Parameters:**

Name | Type |
------ | ------ |
`size` | number |
`alignment` | number |

**Returns:** *[AlignedLockableBuffer](interfaces/alignedlockablebuffer.md)*

___

###  createHasher

▸ **createHasher**(`checksumType?`: [ChecksumType](README.md#checksumtype)): *undefined | [AnyHasher](README.md#anyhasher)*

*Defined in [lib/sparse-stream/shared.ts:77](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/sparse-stream/shared.ts#L77)*

**Parameters:**

Name | Type |
------ | ------ |
`checksumType?` | [ChecksumType](README.md#checksumtype) |

**Returns:** *undefined | [AnyHasher](README.md#anyhasher)*

___

### `Const` createNetworkConfigFiles

▸ **createNetworkConfigFiles**(`networks`: any): *object*

*Defined in [lib/source-destination/configured-source/operations/configure.ts:95](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/operations/configure.ts#L95)*

**Parameters:**

Name | Type |
------ | ------ |
`networks` | any |

**Returns:** *object*

* **ethernet**: *any[]* = _(networks)
			.map('configuration')
			.filter()
			.value()

* **wifi**: *string[]* = _(networks)
			.filter('wifiSsid')
			.map((network, index) => {
				return nmWifiConfig(index + 1, network);
			})
			.value()

___

###  createSparseReaderStateIterator

▸ **createSparseReaderStateIterator**(`blocks`: [BlocksWithChecksum](interfaces/blockswithchecksum.md)[], `verify`: boolean, `generateChecksums`: boolean): *Iterator‹[SparseReaderState](interfaces/sparsereaderstate.md)›*

*Defined in [lib/sparse-stream/shared.ts:97](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/sparse-stream/shared.ts#L97)*

**Parameters:**

Name | Type |
------ | ------ |
`blocks` | [BlocksWithChecksum](interfaces/blockswithchecksum.md)[] |
`verify` | boolean |
`generateChecksums` | boolean |

**Returns:** *Iterator‹[SparseReaderState](interfaces/sparsereaderstate.md)›*

___

###  difference

▸ **difference**<**T**>(`setA`: Set‹T›, `setB`: Set‹T›): *Set‹T›*

*Defined in [lib/utils.ts:90](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/utils.ts#L90)*

**Type parameters:**

▪ **T**

**Parameters:**

Name | Type |
------ | ------ |
`setA` | Set‹T› |
`setB` | Set‹T› |

**Returns:** *Set‹T›*

___

### `Const` driveKey

▸ **driveKey**(`drive`: $Drive): *string*

*Defined in [lib/scanner/adapters/block-device.ts:47](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/scanner/adapters/block-device.ts#L47)*

**Parameters:**

Name | Type |
------ | ------ |
`drive` | $Drive |

**Returns:** *string*

___

### `Const` execFileAsync

▸ **execFileAsync**(`command`: string, `args`: string[], `options`: ExecFileOptions): *Promise‹[ExecResult](interfaces/execresult.md)›*

*Defined in [lib/diskpart.ts:36](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/diskpart.ts#L36)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`command` | string | - |
`args` | string[] | [] |
`options` | ExecFileOptions | {} |

**Returns:** *Promise‹[ExecResult](interfaces/execresult.md)›*

___

### `Const` execute

▸ **execute**(`operation`: any, `disk`: Disk): *Promise‹void›*

*Defined in [lib/source-destination/configured-source/operations/configure.ts:114](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/operations/configure.ts#L114)*

**Parameters:**

Name | Type |
------ | ------ |
`operation` | any |
`disk` | Disk |

**Returns:** *Promise‹void›*

▸ **execute**(`operation`: any, `disk`: Disk): *Promise‹void›*

*Defined in [lib/source-destination/configured-source/operations/copy.ts:39](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/operations/copy.ts#L39)*

**Parameters:**

Name | Type |
------ | ------ |
`operation` | any |
`disk` | Disk |

**Returns:** *Promise‹void›*

___

### `Const` executeOperation

▸ **executeOperation**(`operation`: [Operation](interfaces/operation.md), `disk`: Disk): *Promise‹void›*

*Defined in [lib/source-destination/configured-source/configure.ts:43](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L43)*

**Parameters:**

Name | Type |
------ | ------ |
`operation` | [Operation](interfaces/operation.md) |
`disk` | Disk |

**Returns:** *Promise‹void›*

___

### `Const` getDiskDeviceType

▸ **getDiskDeviceType**(`disk`: Disk): *Promise‹any›*

*Defined in [lib/source-destination/configured-source/configure.ts:68](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L68)*

**Parameters:**

Name | Type |
------ | ------ |
`disk` | Disk |

**Returns:** *Promise‹any›*

___

###  getEta

▸ **getEta**(`current`: number, `total`: number, `speed`: number): *number | undefined*

*Defined in [lib/multi-write.ts:72](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/multi-write.ts#L72)*

**Parameters:**

Name | Type |
------ | ------ |
`current` | number |
`total` | number |
`speed` | number |

**Returns:** *number | undefined*

___

### `Const` getFileStreamFromZipStream

▸ **getFileStreamFromZipStream**(`zipStream`: ReadableStream, `match`: function): *Promise‹ZipStreamEntry›*

*Defined in [lib/zip.ts:21](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/zip.ts#L21)*

**Parameters:**

▪ **zipStream**: *ReadableStream*

▪ **match**: *function*

▸ (`filename`: string): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`filename` | string |

**Returns:** *Promise‹ZipStreamEntry›*

___

### `Const` getPartitionIndex

▸ **getPartitionIndex**(`partition`: number | object): *number*

*Defined in [lib/source-destination/configured-source/configure.ts:50](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L50)*

**Parameters:**

Name | Type |
------ | ------ |
`partition` | number &#124; object |

**Returns:** *number*

___

###  getRootStream

▸ **getRootStream**(`stream`: ReadableStream): *ReadableStream*

*Defined in [lib/source-destination/compressed-source.ts:34](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/compressed-source.ts#L34)*

**Parameters:**

Name | Type |
------ | ------ |
`stream` | ReadableStream |

**Returns:** *ReadableStream*

___

###  isAlignedLockableBuffer

▸ **isAlignedLockableBuffer**(`buffer`: [Buffer](interfaces/alignedlockablebuffer.md#buffer)): *buffer is AlignedLockableBuffer*

*Defined in [lib/aligned-lockable-buffer.ts:47](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/aligned-lockable-buffer.ts#L47)*

**Parameters:**

Name | Type |
------ | ------ |
`buffer` | [Buffer](interfaces/alignedlockablebuffer.md#buffer) |

**Returns:** *buffer is AlignedLockableBuffer*

___

###  isSourceTransform

▸ **isSourceTransform**(`stream`: any): *stream is SourceTransform*

*Defined in [lib/source-destination/compressed-source.ts:30](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/compressed-source.ts#L30)*

**Parameters:**

Name | Type |
------ | ------ |
`stream` | any |

**Returns:** *stream is SourceTransform*

___

###  isTransientError

▸ **isTransientError**(`error`: ErrnoException): *boolean*

*Defined in [lib/errors.ts:65](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/errors.ts#L65)*

**`summary`** Determine whether an error is considered a
transient occurrence, and the operation should be retried
Errors considered potentially temporary are:
  - Mac OS: ENXIO, EBUSY
  - Windows: ENOENT, UNKNOWN
  - Linux: EIO, EBUSY

**Parameters:**

Name | Type |
------ | ------ |
`error` | ErrnoException |

**Returns:** *boolean*

___

###  isntNull

▸ **isntNull**(`x`: any): *boolean*

*Defined in [lib/source-destination/multi-destination.ts:37](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/multi-destination.ts#L37)*

**Parameters:**

Name | Type |
------ | ------ |
`x` | any |

**Returns:** *boolean*

___

###  looksLikeComputeModule

▸ **looksLikeComputeModule**(`description`: string): *boolean*

*Defined in [lib/scanner/adapters/block-device.ts:38](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/scanner/adapters/block-device.ts#L38)*

**Parameters:**

Name | Type |
------ | ------ |
`description` | string |

**Returns:** *boolean*

___

###  makeClassEmitProgressEvents

▸ **makeClassEmitProgressEvents**<**T**>(`Cls`: T, `attribute`: string, `positionAttribute`: string, `interval`: number): *(Anonymous class) & T*

*Defined in [lib/source-destination/progress.ts:33](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/progress.ts#L33)*

**Type parameters:**

▪ **T**: *[Constructor](README.md#constructor)‹EventEmitter›*

**Parameters:**

Name | Type |
------ | ------ |
`Cls` | T |
`attribute` | string |
`positionAttribute` | string |
`interval` | number |

**Returns:** *(Anonymous class) & T*

___

###  matchSupportedExtensions

▸ **matchSupportedExtensions**(`filename`: string): *boolean*

*Defined in [lib/source-destination/zip.ts:66](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/zip.ts#L66)*

**Parameters:**

Name | Type |
------ | ------ |
`filename` | string |

**Returns:** *boolean*

___

### `Const` nmWifiConfig

▸ **nmWifiConfig**(`index`: number, `options`: [WifiConfig](interfaces/wificonfig.md)): *string*

*Defined in [lib/source-destination/configured-source/operations/configure.ts:41](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/operations/configure.ts#L41)*

**Parameters:**

Name | Type |
------ | ------ |
`index` | number |
`options` | [WifiConfig](interfaces/wificonfig.md) |

**Returns:** *string*

___

### `Const` pad

▸ **pad**(`num`: number): *string*

*Defined in [lib/source-destination/configured-source/operations/configure.ts:110](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/operations/configure.ts#L110)*

**Parameters:**

Name | Type |
------ | ------ |
`num` | number |

**Returns:** *string*

___

###  pipeRegularSourceToDestination

▸ **pipeRegularSourceToDestination**(`source`: [SourceDestination](classes/sourcedestination.md), `sourceMetadata`: [Metadata](interfaces/metadata.md), `destination`: [MultiDestination](classes/multidestination.md), `verify`: boolean, `numBuffers`: number, `updateState`: function, `onFail`: function, `onProgress`: function, `_onRootStreamProgress`: function): *Promise‹void›*

*Defined in [lib/multi-write.ts:224](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/multi-write.ts#L224)*

**Parameters:**

▪ **source**: *[SourceDestination](classes/sourcedestination.md)*

▪ **sourceMetadata**: *[Metadata](interfaces/metadata.md)*

▪ **destination**: *[MultiDestination](classes/multidestination.md)*

▪ **verify**: *boolean*

▪ **numBuffers**: *number*

▪ **updateState**: *function*

▸ (`state?`: [WriteStep](README.md#writestep)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`state?` | [WriteStep](README.md#writestep) |

▪ **onFail**: *function*

▸ (`error`: [MultiDestinationError](classes/multidestinationerror.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`error` | [MultiDestinationError](classes/multidestinationerror.md) |

▪ **onProgress**: *function*

▸ (`progress`: [ProgressEvent](interfaces/progressevent.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`progress` | [ProgressEvent](interfaces/progressevent.md) |

▪ **_onRootStreamProgress**: *function*

▸ (`progress`: [ProgressEvent](interfaces/progressevent.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`progress` | [ProgressEvent](interfaces/progressevent.md) |

**Returns:** *Promise‹void›*

___

###  pipeSourceToDestinations

▸ **pipeSourceToDestinations**(`source`: [SourceDestination](classes/sourcedestination.md), `destinations`: [SourceDestination](classes/sourcedestination.md)[], `onFail`: [OnFailFunction](README.md#onfailfunction), `onProgress`: [OnProgressFunction](README.md#onprogressfunction), `verify`: boolean, `numBuffers`: number): *Promise‹[PipeSourceToDestinationsResult](interfaces/pipesourcetodestinationsresult.md)›*

*Defined in [lib/multi-write.ts:82](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/multi-write.ts#L82)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`source` | [SourceDestination](classes/sourcedestination.md) | - |
`destinations` | [SourceDestination](classes/sourcedestination.md)[] | - |
`onFail` | [OnFailFunction](README.md#onfailfunction) | - |
`onProgress` | [OnProgressFunction](README.md#onprogressfunction) | - |
`verify` | boolean | false |
`numBuffers` | number | 16 |

**Returns:** *Promise‹[PipeSourceToDestinationsResult](interfaces/pipesourcetodestinationsresult.md)›*

___

###  pipeSparseSourceToDestination

▸ **pipeSparseSourceToDestination**(`source`: [SourceDestination](classes/sourcedestination.md), `destination`: [MultiDestination](classes/multidestination.md), `verify`: boolean, `numBuffers`: number, `updateState`: function, `onFail`: function, `onProgress`: function, `_onRootStreamProgress`: function): *Promise‹void›*

*Defined in [lib/multi-write.ts:328](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/multi-write.ts#L328)*

**Parameters:**

▪ **source**: *[SourceDestination](classes/sourcedestination.md)*

▪ **destination**: *[MultiDestination](classes/multidestination.md)*

▪ **verify**: *boolean*

▪ **numBuffers**: *number*

▪ **updateState**: *function*

▸ (`state?`: [WriteStep](README.md#writestep)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`state?` | [WriteStep](README.md#writestep) |

▪ **onFail**: *function*

▸ (`error`: [MultiDestinationError](classes/multidestinationerror.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`error` | [MultiDestinationError](classes/multidestinationerror.md) |

▪ **onProgress**: *function*

▸ (`progress`: [ProgressEvent](interfaces/progressevent.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`progress` | [ProgressEvent](interfaces/progressevent.md) |

▪ **_onRootStreamProgress**: *function*

▸ (`progress`: [ProgressEvent](interfaces/progressevent.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`progress` | [ProgressEvent](interfaces/progressevent.md) |

**Returns:** *Promise‹void›*

___

### `Const` randomFilePath

▸ **randomFilePath**(): *string*

*Defined in [lib/tmp.ts:27](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/tmp.ts#L27)*

**Returns:** *string*

___

### `Const` runDiskpart

▸ **runDiskpart**(`commands`: string[]): *Promise‹void›*

*Defined in [lib/diskpart.ts:63](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/diskpart.ts#L63)*

**`summary`** Run a diskpart script

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`commands` | string[] | list of commands to run  |

**Returns:** *Promise‹void›*

___

###  runVerifier

▸ **runVerifier**(`verifier`: [Verifier](classes/verifier.md), `onFail`: function, `onProgress`: function): *Promise‹void›*

*Defined in [lib/multi-write.ts:366](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/multi-write.ts#L366)*

**Parameters:**

▪ **verifier**: *[Verifier](classes/verifier.md)*

▪ **onFail**: *function*

▸ (`error`: [MultiDestinationError](classes/multidestinationerror.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`error` | [MultiDestinationError](classes/multidestinationerror.md) |

▪ **onProgress**: *function*

▸ (`progress`: [ProgressEvent](interfaces/progressevent.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`progress` | [ProgressEvent](interfaces/progressevent.md) |

**Returns:** *Promise‹void›*

___

###  sparseStreamToBuffer

▸ **sparseStreamToBuffer**(`stream`: ReadableStream): *Promise‹[Buffer](interfaces/alignedlockablebuffer.md#buffer)›*

*Defined in [lib/utils.ts:51](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/utils.ts#L51)*

**Parameters:**

Name | Type |
------ | ------ |
`stream` | ReadableStream |

**Returns:** *Promise‹[Buffer](interfaces/alignedlockablebuffer.md#buffer)›*

___

###  streamToBuffer

▸ **streamToBuffer**(`stream`: ReadableStream): *Promise‹[Buffer](interfaces/alignedlockablebuffer.md#buffer)›*

*Defined in [lib/utils.ts:20](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/utils.ts#L20)*

**Parameters:**

Name | Type |
------ | ------ |
`stream` | ReadableStream |

**Returns:** *Promise‹[Buffer](interfaces/alignedlockablebuffer.md#buffer)›*

___

### `Const` tmpFile

▸ **tmpFile**(`keepOpen`: boolean): *Promise‹[TmpFileResult](interfaces/tmpfileresult.md)›*

*Defined in [lib/tmp.ts:36](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/tmp.ts#L36)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`keepOpen` | boolean | true |

**Returns:** *Promise‹[TmpFileResult](interfaces/tmpfileresult.md)›*

___

### `Const` tmpFileDisposer

▸ **tmpFileDisposer**(`keepOpen`: boolean): *Disposer‹[TmpFileResult](interfaces/tmpfileresult.md)›*

*Defined in [lib/tmp.ts:64](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/tmp.ts#L64)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`keepOpen` | boolean | true |

**Returns:** *Disposer‹[TmpFileResult](interfaces/tmpfileresult.md)›*

___

###  verifyOrGenerateChecksum

▸ **verifyOrGenerateChecksum**(`hasher`: [AnyHasher](README.md#anyhasher) | undefined, `blocks`: [BlocksWithChecksum](interfaces/blockswithchecksum.md), `verify`: boolean, `generateChecksums`: boolean): *void*

*Defined in [lib/sparse-stream/shared.ts:123](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/sparse-stream/shared.ts#L123)*

**Parameters:**

Name | Type |
------ | ------ |
`hasher` | [AnyHasher](README.md#anyhasher) &#124; undefined |
`blocks` | [BlocksWithChecksum](interfaces/blockswithchecksum.md) |
`verify` | boolean |
`generateChecksums` | boolean |

**Returns:** *void*

## Object literals

### `Const` ACTIONS

### ▪ **ACTIONS**: *object*

*Defined in [lib/source-destination/configured-source/configure.ts:38](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L38)*

###  configure

• **configure**: *execute* = configureAction

*Defined in [lib/source-destination/configured-source/configure.ts:39](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L39)*

###  copy

• **copy**: *execute* = copyAction

*Defined in [lib/source-destination/configured-source/configure.ts:40](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/source-destination/configured-source/configure.ts#L40)*
