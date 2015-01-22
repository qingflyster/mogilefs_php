mogilefs0.9.2 for php ext class
This class need php5.4+ suppor

mogilefs ext http://pecl.php.net/package/mogilefs/0.9.2

demo:

$config = ['host' => '127.0.0.1', 'port' => 7001, 'domain' => 'file', 'class' => 'img', 'device' => 2]
$mgf = new Mogile($config);

$file = '/tmp/img.jpg';
$key = 'img.jpg';
var_dump($mgf->setFile($key, $file));

var_dump($mgf->fileInfo($key));