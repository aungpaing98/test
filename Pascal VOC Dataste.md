# Pascal VOC Dataset

## Annotation format



```python
fileName.xml

<annotation>
	<folder>VOC2007</folder>
	<filename>000016.jpg</filename>
	<source>
		<database>The VOC2007 Database</database>
		<annotation>PASCAL VOC2007</annotation>
		<image>flickr</image>
		<flickrid>334761423</flickrid>
	</source>
	<owner>
		<flickrid>hesse00</flickrid>
		<name>?</name>
	</owner>
	<size>
		<width>334</width>
		<height>500</height>
		<depth>3</depth>
	</size>
	<segmented>0</segmented>
	<object>
		<name>bicycle</name>
		<pose>Rear</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>92</xmin>
			<ymin>72</ymin>
			<xmax>305</xmax>
			<ymax>473</ymax>
		</bndbox>
	</object>
	<object>
		...
	</object>
</annotation>


```