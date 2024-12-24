SUPSI 2024-25  
Data Visualization course, M-D3202E  
Teacher Giovanni Profeta


# Plastic is Conquering the Oceans
Authors: [Iris Johanna Di Bello](https://www.instagram.com/irisdbl/), [Federica Eoli](https://www.instagram.com/federicaaaeoli/), [Gioia Le Le Wu](https://www.instagram.com/wu_gioia/)

[Plastic is Conquering the Oceans](https://irisdb22.github.io/plastic_is_conquering_the_oceans/)


## Abstract
This webpage shows the results of the research we carried out about one of the major problems related to pollution on Earth, that is the issue of plastics in the oceans. We chose this topic because, sadly, all of the plastic in the ocean is <em>made by humans.</em>
The questions that we asked ourselves are, first of all, how much plastic is there in the oceans? Then we gathered some information on the consequences of these high quantities: we described what garbage patches are and their impact on human health and on the environment.
Subsequently, the main thing we wanted to discover was the source of all this pollution in the different oceans, and in particular which countries were the worst at managing plastic waste.
Lastly, to better explain this, we grouped the countries by continent and analyzed not just the total values, but also the values per capita, so the singular contribute to the issue. In fact, our final goal is to make everyone aware that the total amount of global waste is made by the contribute of every single person on this planet, and that the change is always in the hands of the collectivity, which, however, is made by many individuals.


## Introduction
Do you know which is one of the biggest things made by humans? Well, it's easy. It is <em>waste</em>. Humans are really good at creating waste, but, unfortunately, they're not equally good at disposing it. In this webpage we analyze one of the most popular destinations of mismanaged waste: the ocean. How can we blame it? The ocean is definitely a good destination to choose. However, this choice can have serious consequences on our planet and its inhabitants, starting from the health of animals, of the environment and, last but not least, of humans.
Therefore, the target of this research is basically everyone. In fact, it's important that every human on this planet learns how much their habits could badly affect our environment. More in particular, we would like to draw the attention of the youngest generations, that are the ones that can really make a difference on the long term.




## Data sources

For the first data visualization, "Microplastic in the ocean", we used a dataset from Figshare that provides information about specific points in the ocean, including the latitude and longitude of each point and the corresponding amount of microplastic detected at that location.

For the second data visualization, titled "Countries that emit more plastic in the oceans," we used a dataset from Our World in Data, which provides the annual estimate of plastic emissions per country.

Lastly, for the third visualization, we used two datasets from Our World in Data: one for the total amount of mismanaged plastic waste and the other for the mismanaged plastic waste per capita. 

[Datasource 1](https://figshare.com/articles/dataset/Plastic_Marine_Pollution_Global_Dataset/1015289?file=1483767)
[Datasource 2](https://ourworldindata.org/grapher/plastic-waste-emitted-to-the-ocean)
[Datasource 3.1](https://ourworldindata.org/grapher/plastic-waste-mismanaged)
[Datasource 3.2](https://ourworldindata.org/grapher/mismanaged-plastic-waste-per-capita)

## Data pre-processing
Nunc consequat interdum varius sit amet mattis vulputate. Vehicula ipsum a arcu cursus vitae congue. Odio ut sem nulla pharetra. Accumsan lacus vel facilisis volutpat est velit egestas dui id. Quisque egestas diam in arcu cursus. Eget nulla facilisi etiam dignissim diam. Aenean sed adipiscing diam donec adipiscing tristique. Porttitor massa id neque aliquam. Sem viverra aliquet eget sit amet tellus cras. Scelerisque eu ultrices vitae auctor eu augue ut lectus. Nunc aliquet bibendum enim facilisis gravida neque convallis a. Lacus sed turpis tincidunt id aliquet risus feugiat.


```Python
import pandas as pd

df = pd.read_csv('file.tsv', sep='\t')
print(df.columns)
```

## Data visualizations
Sed enim ut sem viverra aliquet eget sit. Iaculis at erat pellentesque adipiscing commodo. Et pharetra pharetra massa massa ultricies mi quis hendrerit dolor. At tempor commodo ullamcorper a lacus vestibulum sed arcu. Ipsum faucibus vitae aliquet nec ullamcorper sit. Tempus quam pellentesque nec nam aliquam sem et tortor. Turpis egestas sed tempus urna et pharetra pharetra massa. Ridiculus mus mauris vitae ultricies leo integer malesuada nunc vel.

### Data visualization n. 1 - Amount of microplastics in the ocean
Accumsan lacus vel facilisis volutpat est velit egestas dui id. Quisque egestas diam in arcu cursus. Eget nulla facilisi etiam dignissim diam. Aenean sed adipiscing diam donec adipiscing tristique. Porttitor massa id neque aliquam. Sem viverra aliquet eget sit amet tellus cras. Scelerisque eu ultrices vitae auctor eu augue ut lectus.

[<img src="assets/images/01.png" width="800" alt="Placeholder image">]()

### Data visualization n. 2 - Countries that emit more plastic in the oceans
Accumsan lacus vel facilisis volutpat est velit egestas dui id. Quisque egestas diam in arcu cursus. Eget nulla facilisi etiam dignissim diam. Aenean sed adipiscing diam donec adipiscing tristique. Porttitor massa id neque aliquam. Sem viverra aliquet eget sit amet tellus cras. Scelerisque eu ultrices vitae auctor eu augue ut lectus.

[<img src="assets/images/02.png" width="800" alt="Placeholder image">]()

### Data visualization n. 3 - mismanaged waste - total VS per capita
Accumsan lacus vel facilisis volutpat est velit egestas dui id. Quisque egestas diam in arcu cursus. Eget nulla facilisi etiam dignissim diam. Aenean sed adipiscing diam donec adipiscing tristique. Porttitor massa id neque aliquam. Sem viverra aliquet eget sit amet tellus cras. Scelerisque eu ultrices vitae auctor eu augue ut lectus.

[<img src="assets/images/03.png" width="800" alt="Placeholder image">]()


## Key findings
Accumsan lacus vel facilisis volutpat est velit egestas dui id. Quisque egestas diam in arcu cursus. Eget nulla facilisi etiam dignissim diam. Aenean sed adipiscing diam donec adipiscing tristique. Porttitor massa id neque aliquam. Sem viverra aliquet eget sit amet tellus cras. Scelerisque eu ultrices vitae auctor eu augue ut lectus. Nunc aliquet bibendum enim facilisis gravida neque convallis a. Lacus sed turpis tincidunt id aliquet risus feugiat.

## Next steps
Tellus rutrum tellus pellentesque eu. Dictum sit amet justo donec enim. Aliquam malesuada bibendum arcu vitae elementum curabitur vitae. Sed faucibus turpis in eu mi bibendum neque egestas congue. Tellus in metus vulputate eu scelerisque felis imperdiet proin. Dolor magna eget est lorem ipsum dolor. Sit amet mattis vulputate enim nulla. Elit pellentesque habitant morbi tristique senectus et.